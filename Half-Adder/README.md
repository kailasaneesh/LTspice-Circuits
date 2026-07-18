# Half Adder using LTspice

## Overview

This repository contains the LTspice simulation of a Half Adder. It demonstrates the addition of two single-bit binary inputs and generates the corresponding Sum and Carry outputs.

## Circuit Details

- Input A: Pulse Voltage Source (0–5 V)
- Input B: Pulse Voltage Source (0–5 V)
- XOR Gate (Sum Output)
- AND Gate (Carry Output)

## Simulation

Transient Analysis (`.tran 160`)

## Simulation Results

| Parameter | Value |
|-----------|------:|
| Input Voltage | 0–5 V (Pulse) |
| Sum Output | A ⊕ B |
| Carry Output | A · B |
| Analysis | Transient (`.tran 160`) |

The simulated waveforms verify the correct operation of the Half Adder, where the XOR gate produces the Sum output and the AND gate produces the Carry output.
