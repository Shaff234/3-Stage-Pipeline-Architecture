# 3-Stage-Pipeline-Architecture
A compact 3-stage pipelined processor implemented in System Verilog. Features modular design, RISC-V instruction support, and easy simulation with Verilog simulators. Explore the code in the src directory.


Computer Architecture(CA) Final Lab Submission

3-Stage Pipelined Processor in System Verilog


Overview
Welcome to the System Verilog implementation of a simple 3-stage pipelined processor supporting various RISC-V instructions. The design is modular, featuring components such as ALU, Register File, Memory, Control Unit, and more.


File Structure
Processor.sv: The main module that orchestrates all processor components.
alu.sv: Arithmetic Logic Unit for executing arithmetic and logic operations.
reg_file.sv: Register File module managing register read and write operations.
data_mem.sv: Data Memory module handling data memory operations.
csr_reg.sv: Control and Status Register module for system control operations.
controller.sv: Controller module generating control signals based on opcodes and function codes.
PC.v: Program Counter module managing the program counter.
inst_mem.sv: Instruction Memory module storing instructions.
Inst_decode.sv: Instruction Decoder module for decoding instructions.
imm_gen.sv: Immediate Generator module generating immediate values.


How to Use
To simulate the design, use a Verilog simulator like ModelSim. Run the command ./cc.bat.


System Diagram
System Diagram is given in the folder. I tried my best to keep things simple as much as I can.


Muhammad Shaff Ali
Student ID: 2020-CE-07
Instrustor: Sir Hamza/ Sir Afeef
