# Pipelined-Processor

This project involved creating a five-stage (IF-ID-EX-MEM-WB) pipelined processor to simulate the working of pipelined architecture.

Input to the program:
- A set of RISC instructions (in the form of an Instruction Cache) [ICache.txt](https://github.com/akshithsriram/Pipelined-Processor/blob/main/ICache.txt)
- A Register File with 16 8-bit registers [RF.txt](https://github.com/akshithsriram/Pipelined-Processor/blob/main/RF.txt)
- Data Cache [DCache.txt](https://github.com/akshithsriram/Pipelined-Processor/blob/main/DCache.txt) that contains data mapped according to memory addresses.

The program generates two output files:
- DCache.txt indicating all the changes made to the data after the instruction execution is complete.
- Output.txt containing CPU performance statistics like CPI, No. of pipeline stalls, and the reason for each stall (dependency type).

Refer to [PipelinedProcessor.pdf](https://github.com/akshithsriram/Pipelined-Processor/blob/main/PipelinedProcessor.pdf) for full details.
