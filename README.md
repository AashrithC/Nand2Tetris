# Nand2Tetris

This repository contains my implementation of the hardware/low-level portion of the Nand2Tetris course, focusing on the construction of a complete computing architecture from first principles.

---

## Technical Overview

The project involved the hierarchical design and implementation of digital circuits using **Hardware Description Language (HDL)**. Starting from fundamental **boolean logic gates (AND, OR, NOT, XOR, MUX)**, complex combinatorial and sequential logic units were systematically constructed.

---

## Implemented Components

* **Elementary Logic Gates:** AND, OR, NOT, XOR, MUX, DMUX.
* **Arithmetic Logic Unit (ALU):** Capable of performing a full set of arithmetic and logical operations.
* **Registers:** 16-bit registers and program counter (PC).
* **Memory Units:** RAM modules, including an addressable RAM and a screen memory map.
* **Central Processing Unit (CPU):** Designed to fetch, decode, and execute machine language instructions. This custom CPU integrates the ALU, registers, and memory addressing logic to form a functional processing core.
* **Assembler:** A two-pass assembler that translates **Hack assembly language** into the corresponding **binary machine code** for the custom CPU. This includes handling symbolic addresses, labels, and predefined symbols.

---

## Design Principles

* **Modularity:** Each component was designed as a self-contained module, facilitating testing and integration.
* **Hierarchical Design:** Complex components were built by assembling simpler, pre-verified modules.
* **Gate-Level Implementation:** All hardware was constructed directly from elementary logic gates, specifically the Nand gate. 

---

## Simulation and Verification

The implemented hardware components were  tested using **digital logic simulators** to verify their correctness and adherence to specifications.
