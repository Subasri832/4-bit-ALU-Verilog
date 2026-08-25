# 4-Bit ALU Design and Functional Verification using Verilog RTL

## Overview

Designed and functionally verified a 4-bit Arithmetic Logic Unit (ALU) using synthesizable Verilog RTL.

The ALU accepts two 4-bit operands and a 3-bit opcode and supports eight arithmetic and logical operations.

## Operations

| Opcode | Operation |
|--------|-----------|
| 000 | Addition |
| 001 | Subtraction |
| 010 | AND |
| 011 | OR |
| 100 | XOR |
| 101 | NOT |
| 110 | Left Shift |
| 111 | Right Shift |

## Features

- 4-bit arithmetic and logical operations
- Carry flag generation
- Zero flag generation
- Signed overflow detection
- Synthesizable Verilog RTL
- Self-checking verification testbench
- Functional and corner-case testing
- EPWave waveform analysis

## Verification

A self-checking Verilog testbench was developed using reusable tasks.

Test cases include:

- Addition
- Addition with carry
- Signed overflow
- Subtraction
- Zero-result condition
- AND
- OR
- XOR
- NOT
- Left shift
- Right shift

The design was simulated using EDA Playground and verified using EPWave waveforms.

## Tools and Technologies

- Verilog HDL
- RTL Design
- Functional Verification
- EDA Playground
- EPWave

## Project Structure

```text
4-bit-ALU-Verilog/
│
├── alu4.v
├── alu4_tb.v
└── README.md
