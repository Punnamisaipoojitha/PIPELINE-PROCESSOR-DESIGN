# PIPELINE-PROCESSOR-DESIGN

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : PUNNAMISAIPOOJITHA

*INTERN ID* : CT04DL863

*DOMAIN* : VLSI

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION OF THE TASK* :

 This VHDL code implements a basic 4-stage pipelined processor, named `PipelineProcessor`, that performs simple instructions like `ADD`, `SUB`, and `LOAD`. The processor operates on 8-bit wide instructions and data, and uses a clock (`clk`) to drive the pipeline stages. Although minimal, the design demonstrates key concepts of instruction fetching, decoding, execution, and write-back, making it an excellent educational model for understanding pipeline architecture.

The design begins by declaring internal data structures and signals. Two array types, `reg_array` and `mem_array`, represent the register file (with 4 registers) and main memory (with 16 memory locations), respectively. The processor uses a program counter (`PC`) to keep track of the instruction address in memory. The pipeline stages are implemented using signals like `IR_IF` (instruction register in fetch stage), `IR_ID` (instruction register in decode stage), and various other intermediate registers for passing values between stages.

Each clock cycle triggers a pipeline progression, where every stage performs part of an instruction. The fetch stage (`IF`) reads the instruction from memory using the current PC and then increments the PC. In the decode stage (`ID`), the fetched instruction is broken down into its components: `Opcode_ID` to identify the operation, and register fields `Dest_ID`, `Src1_ID`, and `Src2_ID` to identify source and destination registers. The execution stage (`EX`) then performs the appropriate operation based on the opcode—either adding, subtracting, or loading data. Operands for arithmetic instructions are fetched from the register file.

Finally, in the write-back stage (`WB`), the result of the operation (`Result_WB`) is stored back into the destination register, completing the instruction cycle. Despite the simplicity, this model illustrates instruction pipelining, where multiple instructions are at different stages of execution simultaneously. One limitation of this design is the lack of hazard detection and control logic, which would be essential in a real-world pipelined CPU to avoid incorrect data usage or instruction execution. However, this example is useful for learning how pipeline stages are structured and connected in a synchronous system.



*OUTPUT* :


<img width="786" alt="Image" src="https://github.com/user-attachments/assets/adeb2f7c-3c89-4fa6-954f-97f70cbe59b6" />
