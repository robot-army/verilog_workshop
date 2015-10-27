# verilog_workshop
rlab Verilog HDL workshop resources

# Discussion Topics
* HDL philosophy and ways of thinking, in contrast to SDL and even multi-cored parallel software 'methods'
* Structural vs. Behavioural, what is RTL
* Everything is built in hardware, the language 'looks like code' but must describe either real hardware or a test-bench
* Some Verilog is only used inside the definitions of testbenches 
* SystemVerilog is new and brings some useful bits from VHDL, such as synthesizable for loops
* EDA tools, what matters and what doesn't (Use Xilinx Vivado if you don't already know ISE was the take home message, open source tools are coming)
* EDA project steps, eg, verilog code to synthesis to mapping and routing, the relevant simulations at each step
* Ports, input, output, inout
* Data types : Confusion between Reg and wire declaration, Time data type
* Gate level modeling: High impedance, tri state buffer, shared bus etc. 
* Confusion between Blocking and non Blocking Assignment
* Always and Intial Blocks
* Always sensitivity list -> combinatorial or sequential design
* Operators: unary, binary and ternary, reduction operators, concatenation, replication, shift
* Numbers: binary, octal, hex, decimal
* Latch, FF inference,
* Counter, Shift register
* If ifelse else, and case select implementations resulting in either multiplexers or priority encoders
* State machines, coding style to code state machine
* Compiler directives
* Timescale directives
* Synchronous, Asynchronous reset
* Task, function
* Event - @(edge signal), testbench construct, wait -> level triggered
* #delay modelling
* clock frequency, timing constraint
* Interfacing between multiple clock domains and the dangers that lie in designs with multiple asynchronous clocks
* Secure verilog best practices, such as fully assigning variables (eg. 32'hdeadbeef)
* Code coverage and functional coverage metrics in testbenches
* Additional steps required and a basic introduction to ASIC workflow, including scan flip-flops (!!)
* V-Model FPGA project management, and the specific verification steps at each stage
* ASIC/FPGA Design flow, Verification flow, re-iteration based on power constraints, timing constraints etc.
* ASIC Library components, path delays, gate delays, modelling gate delays. What happens in Synthesis, Mapping and Place & Route
* Module instantiation techniques (wiring things up using dot notation, eg .sda_top(.sda_slave) etc)
* Reading files from logic captures into testbenches using the $readmem directives etc
* AXI busses and the high-level design techniques that are required for the 'big chips', like zynq etc.
* Online partial reconfiguration
* PSoC architecture - ARM, Microblaze, where to apply testbench in a Custom IP accelerator in SoC type scenario
