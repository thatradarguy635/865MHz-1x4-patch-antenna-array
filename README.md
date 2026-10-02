# 865 MHz 1×4 Microstrip Patch Antenna Array

CST Studio Suite | RF & Microwave Engineering | Antenna Array Design

---

## Overview

This project presents the design and electromagnetic simulation of an 865 MHz microstrip patch antenna and its extension to a 1×4 linear antenna array.

The antenna is designed and simulated using CST Studio Suite, with the array elements arranged with λ/2 spacing. The project evaluates the impedance characteristics and far-field radiation performance of both the individual antenna element and the four-element array.

The primary simulation outputs include:

- S-parameter response
- VSWR
- Single-element far-field radiation
- 1×4 array far-field radiation

---

## Project Objectives

- Design a microstrip patch antenna operating at 865 MHz.
- Develop a suitable feed and inset configuration for impedance matching.
- Analyze the antenna's simulated S-parameter response.
- Evaluate the VSWR around the design frequency.
- Extend the single patch to a 1×4 linear array.
- Arrange array elements with λ/2 spacing.
- Compare the far-field characteristics of the individual element and array.

---

## Software

- CST Studio Suite
- Electromagnetic simulation and antenna design

---

## Antenna Design Parameters

| Parameter | Value |
|-----------|-------|
| Operating Frequency | 865 MHz |
| Patch Width | 10.5 cm |
| Patch Length | 8.26057 cm |
| Feed Length | 4 cm |
| Feed Width | 0.317485 cm |
| Inset Distance | 1.00129 cm |
| Substrate Height | 0.16 cm |
| Substrate Width | 16.8 cm |
| Substrate Length | 17 cm |
| Wavelength | 34.68 cm |
| Element Spacing | λ/2 |
| Number of Elements | 4 |
| Array Configuration | 1×4 |

---
## Design Methodology

**Patch Design → Feed Optimization → CST Simulation → Single-Element Analysis → 1×4 Array → Far-Field Analysis**
## Antenna Configuration

The project begins with a single microstrip patch antenna designed for operation at 865 MHz.

The antenna geometry includes:

- Rectangular radiating patch
- Microstrip feed
- Inset configuration
- Dielectric substrate
- Conducting ground plane

The design is subsequently extended to a four-element linear array.

The four elements are separated by:

d = λ/2

where the wavelength specified for the design is:

λ = 34.68 cm

---

## Simulation Results

### S11 / Return Loss

The CST simulation produces the S-parameter response of the antenna.

The simulated response shows a resonance around the target operating frequency of 865 MHz, with a minimum S11 of approximately:

S11 ≈ -35 dB

This indicates a strong simulated impedance match around the design frequency.

---

### VSWR

The simulated VSWR around the operating frequency is approximately:

VSWR ≈ 1.04

at 865 MHz.

A low VSWR corresponds to improved power transfer between the feed and antenna under the simulated conditions.

---

### Far-Field Analysis

Far-field simulations were performed for both:

1. The individual patch antenna
2. The 1×4 antenna array

The CST results contain separate far-field simulations at:

f = 865 MHz

The array simulation allows the radiation characteristics of the four-element configuration to be investigated relative to the individual antenna element.

---

## Results Included

The repository contains the CST model and associated simulation documentation.

CST/
└── Patch_Antenna.cst

documentation/
└── Results.docx

The result image filenames above represent the recommended repository organization. They can be added after exporting the corresponding CST plots.

---


## Engineering Analysis

The simulation demonstrates the electromagnetic behavior of a microstrip patch antenna at the selected operating frequency and its extension into a linear array.

The individual element provides the fundamental antenna response, while the 1×4 configuration enables investigation of the effect of multiple radiating elements and their spacing on the far-field response.

The use of λ/2 element spacing provides a controlled baseline for studying array radiation characteristics.

---

## Future Work

Potential extensions of the design include:

- Optimization of patch dimensions
- Optimization of feed and inset parameters
- Parametric optimization of element spacing
- Analysis of mutual coupling between array elements
- Gain and directivity optimization
- Beam-steering implementation
- Phase-controlled array excitation
- Comparison between simulated and measured results
- Fabrication and experimental validation

---

## Key Technologies

### RF and Microwave Engineering

- Microstrip antenna design
- Antenna arrays
- Electromagnetic simulation
- S-parameter analysis
- VSWR analysis
- Far-field analysis
- Array element spacing

### Software

- CST Studio Suite

---

## Author

Soham Mayekar

## Disclaimer

This repository contains simulation-based antenna design work. The reported results are based on the CST electromagnetic simulation model and simulation conditions used for the project.
