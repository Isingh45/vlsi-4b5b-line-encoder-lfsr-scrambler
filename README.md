# VLSI 4B/5B Line Encoder with Dual LFSR Scrambling

## Overview

This project implements a digital communication pipeline featuring 4B/5B encoding, dual 16-bit LFSR scrambling/descrambling, serialization, and decoding logic. The system was developed using LogicWorks for schematic design and Magic VLSI for CMOS layout implementation and verification.

The project demonstrates a hierarchical VLSI design flow from digital logic design and subsystem verification to physical layout generation and simulation-based validation.

---

## Key Features

* 4B/5B Encoder
* 4B/5B Decoder
* Dual 16-bit XNOR-LFSR Scrambler/Descrambler
* 5-bit Shift Register
* 5×1 Serializer Multiplexer
* Mod-5 Counter
* CMOS Layout Design in Magic VLSI
* IRSIM-Based Functional Verification
* Hierarchical Digital System Integration

---

## System Architecture

The communication pipeline consists of the following major subsystems:

1. 4B/5B Encoder
2. Dual 16-bit LFSR Scrambler
3. Mod-5 Counter
4. 5×1 Serializer Multiplexer
5. 5-bit Shift Register
6. Dual 16-bit LFSR Descrambler
7. 4B/5B Decoder

The architecture improves transition density during serial transmission while demonstrating digital communication concepts commonly used in high-speed communication systems.

---

## Design Methodology

### Logic Design

* Developed subsystem schematics using LogicWorks.
* Implemented encoder, decoder, serializer, counter, shift register, and LFSR modules.
* Verified functional correctness through hierarchical testing and simulation.

### Physical Design

* Implemented CMOS layouts using Magic VLSI.
* Applied hierarchical layout techniques to construct larger system modules from validated subcircuits.
* Performed extraction and layout verification across multiple design stages.

### Verification

* Utilized IRSIM waveform analysis to validate subsystem functionality.
* Verified serializer operation, counter sequencing, shift-register behavior, and communication-path timing.
* Confirmed correct operation across integrated pipeline stages.

---

## Technologies Used

* LogicWorks
* Magic VLSI
* IRSIM
* CMOS Design
* Digital Logic Design
* VLSI Layout Design

---

## Repository Contents

```text
Report/
    CMPE480_Final_Report.pdf

Presentation/
    CMPE480_VLSI_Project_Presentation.pptx

Design_Files/
    Count.cct
    ShiftReg5.cct
    mux5x1.cct
    DFlipFlop.cct
    2nd_stage.cct
    3rd_stage.cct
```

---

## My Contributions

* Developed and verified hierarchical LogicWorks schematics.
* Contributed to encoder, serializer, counter, shift-register, and LFSR subsystem development.
* Implemented CMOS layouts and extraction workflows in Magic VLSI.
* Performed simulation-based verification using IRSIM waveform analysis.
* Assisted with system integration, validation, documentation, and final project presentation.

---

## Project Status

The project successfully demonstrated communication-pipeline functionality through schematic verification, physical layout implementation, and simulation-based validation.

Future improvements may include expanded system integration, additional long-duration validation testing, and further physical design optimization.

---

## Academic Context

**California State University, East Bay**

**CMPE 480 – VLSI Circuit Design/Layout**

**Spring 2026**
