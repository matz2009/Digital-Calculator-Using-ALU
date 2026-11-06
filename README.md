# Digital Calculator Using ALU

## Project Overview
This project implements a Digital Calculator using an Arithmetic Logic Unit (ALU) in **SystemVerilog**. It performs arithmetic and bitwise logical operations on two 8-bit input operands based on a 4-bit opcode.

## Features
- Addition
- Subtraction
- Multiplication
- Division
- Bitwise AND
- Bitwise OR
- Bitwise XOR
- Bitwise NOT
- Carry detection
- Borrow detection
- Division-by-zero handling
- Zero-result detection

## Supported Operations

| Opcode | Operation | Description |
|:---:|---|---|
| 0000 | ADD | Addition (A + B) |
| 0001 | SUB | Subtraction (A - B) |
| 0010 | MUL | Multiplication (A * B) |
| 0011 | DIV | Division (A / B) |
| 0100 | AND | Bitwise AND |
| 0101 | OR | Bitwise OR |
| 0110 | XOR | Bitwise XOR |
| 0111 | NOT | Bitwise NOT of A |

## Design Specifications

| Parameter | Specification |
|---|---|
| HDL | SystemVerilog |
| Design Module | digital_calculator |
| Testbench Module | tb_digital_calculator |
| Input A | 8-bit |
| Input B | 8-bit |
| Opcode | 4-bit |
| Result | 16-bit |
| Design Type | Combinational Logic |

## Project Structure

```text
Digital-Calculator-Using-ALU/
│
├── design.sv
├── testbench.sv
└── README.md
```

## Simulation Test Cases

| Operation | Inputs | Expected Result |
|---|---|---:|
| ADD | 20 + 10 | 30 |
| SUB | 50 - 20 | 30 |
| MUL | 10 * 5 | 50 |
| DIV | 100 / 10 | 10 |
| AND | 204 & 170 | 136 |
| OR | 204 \| 170 | 238 |
| XOR | 204 ^ 170 | 102 |
| NOT | ~204 | 51 |

## Simulation and Verification

The design and testbench are simulated using **EDA Playground**.

The testbench applies input combinations for all eight operations and generates a VCD waveform file (`dump.vcd`) for waveform analysis.

## Tools and Technologies
- SystemVerilog
- EDA Playground
- HDL Simulation
- VCD Waveform Analysis

## Author
Mathi Sree R
