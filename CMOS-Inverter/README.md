# CMOS Inverter using LTspice

## Overview

This repository contains the LTspice simulation of a basic CMOS inverter. It demonstrates the operation of a CMOS NOT gate by producing an output that is the logical inverse of the input signal.

## Circuit Details

- Supply Voltage (VDD): 1 V
- PMOS Transistor
- NMOS Transistor
- Pulse Voltage Source

## Simulation

Transient Analysis (`.tran 200ms`)

## Simulation Results

| Parameter | Value |
|-----------|------:|
| Supply Voltage | 1 V |
| Input Voltage | 0–1 V (Pulse) |
| Output Voltage | Inverted Input |
| Analysis | Transient (`.tran 200ms`) |

The simulated output verifies the switching operation of the CMOS inverter, where a LOW input produces a HIGH output and a HIGH input produces a LOW output.
