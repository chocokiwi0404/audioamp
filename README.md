# Four-Stage Audio Amplifier

A discrete transistor-based **four-stage audio amplifier** designed to amplify low-level audio signals while maintaining **low Total Harmonic Distortion (THD)** and a **flat frequency response** across the audible range (20 Hz – 20 kHz).

The project includes complete circuit design, theoretical derivations, LTspice simulations, hardware implementation, and performance validation.

---

## Features

- Differential amplifier pre-amplifier with high CMRR
- Common-emitter voltage gain stage
- Active band-pass filter (20 Hz – 20 kHz)
- Class-AB push-pull power amplifier
- LTspice simulation and hardware verification
- Mathematical derivations for gain, impedance, and frequency response

---

## System Architecture

```
Audio Input
      │
      ▼
Differential Amplifier
      │
      ▼
Common-Emitter Gain Stage
      │
      ▼
Active Band-Pass Filter
      │
      ▼
Class-AB Power Amplifier
      │
      ▼
    10 Ω Speaker
```

---

## Repository Structure

```
.
├── differential_amp/      # LTspice files and hardware images for the differential amplifier
├── gain_stage/            # Common-emitter gain stage design and simulations
├── filter/                # Active band-pass filter design
├── power_amp/             # Class-AB power amplifier
├── full_circuit/          # Complete integrated amplifier simulation
├── Project_Report.pdf     # Final project report with derivations and results
├── Rough_design_ref.pdf   # Initial design calculations and reference notes
└── README.md
```

---

## Specifications

| Parameter | Value |
|-----------|-------|
| Supply Voltage | ±5 V |
| Frequency Response | 20 Hz – 20 kHz |
| Speaker Load | 10 Ω |
| Output Power | ~0.7 W |
| Amplifier Topology | Four-Stage Analog Amplifier |
| Simulation Software | LTspice |

---

## Project Stages

### 1. Differential Amplifier
- Amplifies low-level input signals
- High input impedance
- Good common-mode noise rejection

### 2. Common-Emitter Gain Stage
- Provides the majority of the voltage gain
- Optimized transistor biasing for maximum output swing

### 3. Active Band-Pass Filter
- Passband covering the audible frequency range
- Removes low-frequency hum and high-frequency noise
- Unity mid-band gain

### 4. Class-AB Power Amplifier
- Push-pull output stage
- Low crossover distortion
- Drives a 10 Ω speaker with approximately 0.7 W output power

---

## Validation

The complete amplifier was validated through:

- Analytical derivations
- LTspice simulations
- Hardware implementation
- Oscilloscope measurements

Simulation and hardware results showed close agreement with theoretical calculations.

---

## Tools Used

- LTspice
- Analog Circuit Design
- BJT Small-Signal Analysis

---

## Authors

- **Vedant Zope**
- **Kavya Pandey**
