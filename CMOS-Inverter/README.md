# CMOS Inverter using LTspice

## Overview

This repository contains the LTspice simulation of a CMOS inverter. It demonstrates the operation of a basic CMOS logic gate using one PMOS transistor and one NMOS transistor, where the output is the logical inverse of the input.

## Circuit Details

- Supply Voltage: 1 V
- Input Voltage: Pulse Source (0–1 V)
- One PMOS Transistor
- One NMOS Transistor

## Simulation

Transient Analysis (`.tran 200ms`)

## Simulation Results

| Parameter | Value |
|-----------|------:|
| Supply Voltage | 1 V |
| Input Voltage | 0–1 V (Pulse) |
| Output Voltage | Inverted Input |
| Analysis | Transient (`.tran 200ms`) |

The simulated output verifies the operation of the CMOS inverter, where the output is HIGH when the input is LOW and LOW when the input is HIGH.
