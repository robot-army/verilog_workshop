# verilog_workshop
rlab Verilog HDL workshop resources

# Discussion Topics
HDL philosophy and ways of thinking, in contrast to SDL and even multi-cored parallel software 'methods'
Structural vs. Behavioural, what is RTL
Everything is built in hardware, the language 'looks like code' but must describe either real hardware or a test-bench
Some Verilog is only used inside the definitions of testbenches 
SystemVerilog is new and brings some useful bits from VHDL, such as synthesizable for loops
EDA tools, what matters and what doesn't (Use Xilinx Vivado if you don't already know ISE was the take home message, open source tools are coming)
EDA project steps, eg, verilog code to synthesis to mapping and routing, the relevant simulations at each step
Timescale directives
Interfacing between multiple clock domains and the dangers that lie in designs with multiple asynchronous clocks
Secure verilog best practices, such as fully assigning variables (eg. 32'hdeadbeef)
Code coverage and functional coverage metrics in testbenches
Additional steps required and a basic introduction to ASIC workflow, including scan flip-flops (!!)
V-Model FPGA project management, and the specific verification steps at each stage
Module instantiation techniques (wiring things up using dot notation, eg .sda_top(.sda_slave) etc)
If ifelse else, and case select implementations resulting in either multiplexers or priority encoders
Reading files from logic captures into testbenches using the $readmem directives etc
AXI busses and the high-level design techniques that are required for the 'big chips', like zynq etc.
Online partial reconfiguration
