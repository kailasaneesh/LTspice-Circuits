# Full Adder using LTspice

## Overview

This repository contains the LTspice simulation of a Full Adder. It demonstrates the addition of three single-bit binary inputs (A, B, and Carry-In) and generates the corresponding Sum and Carry outputs.

## Circuit Details

- Input A: Pulse Voltage Source (0–1 V)
- Input B: Pulse Voltage Source (0–1 V)
- Carry-In (Cin): Pulse Voltage Source (0–1 V)
- XOR Gates (Sum Output)
- AND Gates (Carry Generation)
- OR Gate (Final Carry Output)

## Simulation

Transient Analysis (`.tran 8ms`)

## Simulation Results

| Parameter | Value |
|-----------|------:|
| Supply Voltage | 1 V |
| Input Voltage | 0–1 V (Pulse) |
| Sum Output | A ⊕ B ⊕ Cin |
| Carry Output | (A·B) + (Cin·(A ⊕ B)) |
| Analysis | Transient (`.tran 8ms`) |

The simulated waveforms verify the correct operation of the Full Adder by generating the appropriate Sum and Carry outputs for all input combinations.
