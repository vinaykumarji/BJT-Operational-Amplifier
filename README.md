# BJT Operational Amplifier

### Design, Simulation and Hardware Implementation

A discrete operational amplifier designed using Bipolar Junction
Transistors (BJTs), simulated using LTspice, and implemented
physically using discrete components on a breadboard.

This project explores transistor-level analog circuit design,
including differential amplification, current mirrors, active loads,
Darlington configurations, and closed-loop amplifier applications.

---

## Project Team

- **Vinay Kumar**
- **Kavish**
- **Hardik Sharma**

**Institution:** Indian Institute of Technology Madras  
**Programme:** BS in Electronic Systems  
**Project Date:** September 2026

---

## Objectives

- Design an operational amplifier using discrete BJTs.
- Understand differential amplifiers and current mirrors.
- Implement a PNP transistor active load.
- Develop a Darlington amplification stage.
- Simulate the circuit using LTspice.
- Implement and test the circuit on a breadboard.
- Verify inverting and non-inverting amplifier configurations.
- Compare theoretical and practical results.

---

## Circuit Architecture

The design incorporates the following stages:

1. Differential Input Stage
2. Tail Current Mirror
3. PNP Active Load
4. Darlington Current Mirror
5. Darlington Stage
6. Output Stage

**Power supply:** +12 V and -12 V dual supply.

---

## Tools and Components

- **LTspice** — Circuit simulation and analysis
- **KiCad** — Electronic design tools
- **BJTs** — Transistor-level circuit implementation
- **Function Generator** — Input signal generation
- **Digital Oscilloscope** — Waveform measurement
- **Breadboard** — Physical circuit implementation

---

## Repository Contents

| File | Description |
|---|---|
| `BJT Operational Amplifier.asc` | LTspice operational amplifier schematic |
| `Input Sin wave.jpeg` | Input sinusoidal waveform |
| `Inverting_gain 2.jpeg` | Inverting amplifier experimental waveform |
| `Inverting gain 3.jpeg` | Additional inverting amplifier waveform |
| `non-inverting gain 3.jpeg` | Non-inverting amplifier waveform |
| `breradbord.jpeg` | Physical breadboard implementation |
| `Two-Stage Discrete BJT Operational Amplifier...` | Project report |

---

## Experimental Results

The amplifier was tested using inverting and non-inverting configurations.

| Parameter | Theoretical Gain | Measured Gain |
|---|---:|---:|
| Inverting Amplifier | -2 | Approximately -2.16 |
| Non-Inverting Amplifier | 3 | Approximately 3.22 |

The reported measurements were taken at approximately 1 kHz.

### Inverting Amplifier

The inverting amplifier uses negative feedback to produce an output
that is approximately 180 degrees out of phase with the input.

### Non-Inverting Amplifier

The non-inverting amplifier produces an output that is in phase
with the input signal.

---

## Hardware Implementation

The circuit was assembled using discrete BJTs and passive components
on a breadboard.

The implementation was developed progressively, beginning with the
current mirror and differential pair, followed by the active load
and Darlington stage.

Practical testing highlighted challenges involving transistor
matching, power-supply limitations, temperature variation,
component failures, and differences between simulation and hardware.

---

## Learning Outcomes

- BJT biasing and operating-point analysis
- Differential amplifier design
- Current mirror implementation
- Active-load amplification
- Darlington transistor configurations
- Feedback and closed-loop gain
- LTspice simulation
- Hardware debugging and waveform analysis

---

## Project Documentation

The accompanying project report describes the circuit architecture,
design methodology, practical implementation, experimental results,
and challenges encountered during development.

---

## Disclaimer

This project is an academic prototype intended for learning and
experimental study of analog electronics. It is not presented as
a precision or production-ready operational amplifier.

---

**Developed by Vinay Kumar, Kavish, and Hardik Sharma**  
Indian Institute of Technology Madras
