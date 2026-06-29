# VLSI Design: 4B/5B Communication System with Dual 16-bit LFSR Scrambling

## Overview

This project implements a complete digital communication pipeline featuring 4B/5B line encoding, serial data transmission, dual 16-bit LFSR scrambling/descrambling, and end-to-end data recovery. The system was developed using a hierarchical CMOS design methodology, progressing from digital logic design and subsystem verification to physical layout implementation and simulation-based validation.

The project demonstrates core VLSI design concepts including combinational and sequential logic design, hierarchical circuit integration, CMOS layout development, and functional verification.

---

## Key Features

* 4B/5B Line Encoder
* 4B/5B Line Decoder
* Dual 16-bit XNOR-LFSR Scrambler/Descrambler
* 5×1 Serializer Multiplexer
* Synchronous Mod-5 Counter
* 5-bit Shift Register
* Hierarchical CMOS Design
* Magic VLSI Physical Layout
* IRSIM Functional Verification

---

## System Architecture

The communication pipeline consists of the following major subsystems:

```
4-bit Parallel Input
        ↓
4B/5B Encoder
        ↓
Synchronous Mod-5 Counter
        ↓
5×1 Serializer Multiplexer
        ↓
Dual 16-bit LFSR Scrambler
        ↓
Serial Transmission
        ↓
Dual 16-bit LFSR Descrambler
        ↓
5-bit Shift Register
        ↓
4B/5B Decoder
        ↓
Recovered 4-bit Output
```

The architecture improves transition density during serial communication while demonstrating digital communication concepts commonly used in high-speed communication systems.

---

## Design Methodology

### Digital Logic Design

* Developed subsystem schematics using LogicWorks
* Designed encoder, decoder, serializer, Mod-5 counter, shift register, and LFSR modules
* Applied a hierarchical design methodology to integrate validated subsystems into a complete communication pipeline
* Verified subsystem functionality through simulation before full-system integration

### Physical Design

* Implemented CMOS layouts using Magic VLSI
* Built reusable standard-cell based layouts using hierarchical design techniques
* Performed layout extraction and verification throughout the physical design process

### Verification

* Validated subsystem functionality using IRSIM waveform analysis
* Verified encoder and decoder operation across all 16 possible input combinations
* Confirmed serializer operation, counter sequencing, shift-register behavior, and integrated communication-path functionality

---

## Technologies Used

* LogicWorks
* Magic VLSI
* IRSIM
* CMOS Layout Design
* Digital Logic Design
* VLSI Circuit Design
* Sequential Logic Design
* Combinational Logic Design

---

## Repository Structure

```
Report/
    CMPE480_Final_Report.pdf

Presentation/
    CMPE480_VLSI_Project_Presentation.pptx

Design_Files/
    Encoder
    Mod-5 Counter
    5×1 Multiplexer
    Shift Register
    D Flip-Flop
    Integrated Design Files
```

---

## My Contributions

* Developed and verified hierarchical LogicWorks schematics for multiple digital subsystems
* Contributed to the design and integration of the encoder, serializer, Mod-5 counter, shift register, and LFSR communication pipeline
* Implemented CMOS layouts using Magic VLSI and participated in layout extraction and verification
* Performed functional verification using IRSIM waveform analysis
* Assisted with system integration, validation, technical documentation, and final project presentation

---

## Project Outcome

This project successfully demonstrated the complete design flow of a hierarchical VLSI communication system—from digital logic design and subsystem development to CMOS layout implementation and simulation-based verification.

The project strengthened practical experience in digital system design, hierarchical circuit integration, physical layout design, and verification methodologies commonly used in modern VLSI engineering.

---

## Academic Context

**California State University, East Bay**

**CMPE 480 – VLSI Circuit Design/Layout**

**Spring 2026**

**Team Members**

* Sukhpinder Singh
* Inderpal Singh
* Wasi Mohammed
