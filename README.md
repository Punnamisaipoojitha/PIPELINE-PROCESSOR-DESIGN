# PIPELINE-PROCESSOR-DESIGN

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : PUNNAMISAIPOOJITHA

*INTERN ID* : CT04DL863

*DOMAIN* : VLSI

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION OF THE TASK* :

This project involves the design and simulation of a simple 4-stage pipelined processor using Verilog HDL, as part of the CodTech internship deliverables. The objective is to implement a basic processor architecture capable of executing fundamental instructions such as ADD, SUB, and LOAD, while demonstrating the concepts of pipelining—a core principle in modern CPU design for improving performance and throughput.

The processor is divided into four key pipeline stages: Instruction Fetch (IF), Instruction Decode (ID), Execution (EX), and Memory/Write Back (MEM/WB). In the IF stage, the instruction is fetched from memory based on the program counter. The ID stage decodes the instruction and prepares operands by reading from the register file. In the EX stage, arithmetic or logic operations like ADD or SUB are performed. The final MEM/WB stage handles memory access for LOAD instructions or writes the result back to the register file.

This pipelined architecture allows multiple instructions to be in different stages of execution simultaneously, increasing instruction throughput. Special care is taken in the design to handle basic hazards and maintain data flow integrity between stages. The design is tested through a simulation environment that shows the operation of each instruction as it passes through the pipeline stages. This includes cycle-by-cycle tracking of instruction flow, showcasing parallelism and the benefits of pipelining.

The final deliverables include the Verilog implementation of the processor, a testbench demonstrating its functionality, and simulation results highlighting the internal behavior of each pipeline stage. This project demonstrates an understanding of CPU microarchitecture and pipelined execution, providing practical insight into performance-oriented processor design and strengthening the student's foundational knowledge in digital system design.


*OUTPUT* :

<img width="786" alt="Image" src="https://github.com/user-attachments/assets/adeb2f7c-3c89-4fa6-954f-97f70cbe59b6" />
