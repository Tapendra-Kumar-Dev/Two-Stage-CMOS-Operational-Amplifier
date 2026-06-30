# Two-Stage CMOS Operational Amplifier

## Overview

This project presents the design and simulation of a **two-stage Miller-compensated CMOS operational amplifier** using **LTspice** and ideal MOSFET models. The amplifier was characterized through DC, AC, and transient analyses to evaluate its small-signal and large-signal performance.

## Performance Summary

| Parameter | Value |
|-----------|--------:|
| Open-Loop DC Gain | **121.29 dB** |
| Unity Gain Bandwidth (UGB) | **9.12 MHz** |
| Phase Margin | **78.5°** |
| CMRR | **127.32 dB** |
| PSRR+ | **127.07 dB** |
| PSRR− | **166.08 dB** |
| Slew Rate | **10.28 V/µs** |
| Output Swing | **+2.40 V / −2.31 V** |

## Simulation Methodology

- **DC Analysis:** Verified transistor operating point and output bias.
- **AC Analysis:** Measured open-loop gain, UGB, and phase margin using Bode plots.
- **CMRR & PSRR:** Evaluated rejection performance by applying AC excitation to the inputs and supply rails while maintaining the bias point.
- **Transient Analysis:** Measured slew rate and output voltage swing using a unity-gain buffer configuration.

## Software Used

- LTspice
- Ideal CMOS MOSFET Models
