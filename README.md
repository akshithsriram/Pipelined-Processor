# Pipelined-Processor

This project involved creating a five-stage (IF-ID-EX-MEM-WB) pipelined processor to simulate the working of pipelined architecture.

Input to the program:
- A set of RISC instructions (in the form of an Instruction Cache) [ICache.txt](https://github.com/akshithsriram/Pipelined-Processor/blob/main/ICache.txt)
- A Register File with 16 8-bit registers [RF.txt](https://github.com/akshithsriram/Pipelined-Processor/blob/main/RF.txt)
- Data Cache [DCache.txt](https://github.com/akshithsriram/Pipelined-Processor/blob/main/DCache.txt) that contains data mapped according to memory addresses.

The program generates two output files:
- DCache.txt indicating all the changes made to the data after the instruction execution is complete.
- Output.txt containing CPU performance statistics like CPI, No. of pipeline stalls, and the reason for each stall (dependency type).

Skills Involved:
- A good understanding of the pipelined processor architecture.
- Knowledge about Reduced Instruction Set Architecture (RISC).
- Implementation of Data Path and Control Path through functions.
- Decoding instructions to determine the operation type.
- Handling Read-After-Write (RAW) and Control Hazards.
- File I/O to fetch data, instructions and generate output files.

Refer to [PipelinedProcessor.pdf](https://github.com/akshithsriram/Pipelined-Processor/blob/main/PipelinedProcessor.pdf) for full details.

This project was created as a part of the course CS2610: Computer Organization and Architecture Lab, taught by [Prof. Madhu Mutyam](http://www.cse.iitm.ac.in/~madhu/) of IIT Madras.
