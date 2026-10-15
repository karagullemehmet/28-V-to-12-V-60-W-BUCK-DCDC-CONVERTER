# 28 V to 12 V / 60 W Buck DC/DC Converter

**Power Electronics Design and Simulation Project**

A 100 kHz Buck DC/DC converter designed and analyzed using MATLAB/Simulink, Simscape Electrical, and LTspice.

## Technical Specifications

| Parameter | Value |
|---|---|
| Input Voltage | 28 V DC |
| Output Voltage | 12 V DC |
| Output Power | 60 W |
| Switching Frequency | 100 kHz |
| Inductor | 47 µH |
| Output Capacitor | 220 µF |

## Engineering Work

- Buck converter modeling and closed-loop PI voltage control
- Small-signal modeling, Bode plots, pole-zero and stability analysis
- Soft-start, UVLO, OVP and cycle-by-cycle OCP protection
- MOSFET and diode loss, thermal and efficiency analysis
- Line/load transient response and component tolerance analysis
- LTspice–Simscape cross-validation

## Key Results

- Regulated output near 12 V across tested input and load conditions
- 95.29% simulated efficiency for the evaluated LTspice configuration
- LTspice–Simscape DC output discrepancy reduced from 6.48% to approximately 0.61% in a matched-duty sensitivity test

## Technical Report

[View Full Technical Report](docs/Buck_Converter_Technical_Report.pdf)

*Simulation-based engineering project; no physical prototype or hardware certification is claimed.*
