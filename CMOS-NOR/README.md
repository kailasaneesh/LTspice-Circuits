# CMOS NOR Gate using LTspice

## Overview

This repository contains the LTspice simulation of a 2-input CMOS NOR gate. It demonstrates the operation of a basic CMOS logic gate using PMOS and NMOS transistors, where the output is HIGH only when both inputs are LOW.

## Circuit Details

- Supply Voltage: 5 V
- Input A: Pulse Voltage Source (0–5 V)
- Input B: Pulse Voltage Source (0–5 V)
- Two PMOS Transistors
- Two NMOS Transistors

## Simulation

Transient Analysis (`.tran 80ms`)

## Simulation Results

| Parameter | Value |
|-----------|------:|
| Supply Voltage | 5 V |
| Input Voltage | 0–5 V (Pulse) |
| Output Voltage | NOR Output |
| Analysis | Transient (`.tran 80ms`) |

The simulated output verifies the operation of the CMOS NOR gate, where the output remains HIGH only when both inputs are LOW.
