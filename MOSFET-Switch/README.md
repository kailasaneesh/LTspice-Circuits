# MOSFET as a Switch using LTspice

## Overview

This repository contains the LTspice simulation of a MOSFET used as an electronic switch. A pulse input is applied to the gate to demonstrate the ON and OFF switching operation of the MOSFET.

## Circuit Details

- Supply Voltage: 12 V
- Gate Pulse: 0 V to 5 V
- Gate Resistor (R1): 100 Ω
- Pull-up Resistor (R2): 4.7 kΩ
- MOSFET: Si7336ADP

## Simulation Results

| Input Voltage | MOSFET State | Output Voltage |
|---------------|-------------:|---------------:|
| 0 V | OFF | 12 V |
| 5 V | ON | 0 V |

The simulation verifies the switching behavior of the MOSFET.
