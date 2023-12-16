# MySPIM-Stimulator

This project involves building the core of a MIPS processor simulator called MySPIM using C language on Unix or PC. The simulator reads MIPS machine codes from a file, simulating the MIPS processor cycle-by-cycle. The goal is to implement a single-cycle datapath and control signals.

Specifications
Instructions to be Simulated
Simulate 14 MIPS instructions (see Figure 1 in the document).

Registers
Handle 32 general-purpose registers.

Memory Usage
Memory size: 64kB (Address 0x0000 to 0xFFFF).
Program starts at 0x4000.
All instructions word-aligned.
Memory treated as one segment.
Memory initialized to zero at the program start.
Conditions for Halting
Illegal instruction.
Jumping to non-word-aligned address.
lw or sw address not word-aligned.
Accessing data or jumping beyond memory bounds.
Input Machine Code File Format
MySPIM takes hexadecimal formatted machine codes from a .asc file.
