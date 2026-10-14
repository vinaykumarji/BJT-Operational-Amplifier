# BJT Operational Amplifier

A transistor-level operational amplifier designed and implemented
using discrete Bipolar Junction Transistors (BJTs).

The project covers circuit design, LTspice simulation, breadboard
implementation, and experimental verification of basic amplifier
configurations.

## Project Team

- Vinay Kumar
- Kavish
- Hardik Sharma

Indian Institute of Technology Madras  
BS in Electronic Systems

## Project Objectives

- Design a BJT-based operational amplifier.
- Implement a differential input stage.
- Design current mirrors and a PNP active load.
- Develop a Darlington amplification stage.
- Simulate the circuit using LTspice.
- Build and test the circuit using discrete components.
- Verify inverting and non-inverting amplifier configurations.

## Circuit Architecture

The circuit consists of:

1. Differential Input Stage
2. Tail Current Mirror
3. PNP Active Load
4. Darlington Current Mirror
5. Darlington Stage
6. Output Stage

The design uses a dual power supply of +12 V and -12 V.

## Experimental Results

| Configuration | Theoretical Gain | Measured Gain |
|---|---:|---:|
| Inverting Amplifier | -2 | Approximately -2.16 |
| Non-Inverting Amplifier | 3 | Approximately 3.22 |

The reported measurements were taken at approximately 1 kHz.

## Tools Used

- LTspice
- KiCad
- Function Generator
- Digital Oscilloscope
- Discrete BJTs and passive components

## Repository Contents

- `LTspice/` — Circuit simulation files
- `KiCad/` — Circuit design files
- `Results/` — Experimental waveforms
- `Hardware/` — Physical implementation photographs
- `Documentation/` — Project report

These folders will contain the corresponding project files as they
are added to the repository.

## Key Learning Outcomes

- BJT biasing and current mirrors
- Differential amplifier design
- Active-load amplification
- Darlington transistor configurations
- Feedback and closed-loop gain
- Circuit simulation and hardware debugging
- Practical analog electronics

## Project Report

The project report documents the design process, experimental
measurements, and challenges encountered during implementation.

---

Academic project developed by Vinay Kumar, Kavish, and Hardik Sharma.
