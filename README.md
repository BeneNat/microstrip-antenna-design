# Microstrip Antenna Design (2.4 GHz)

Project repository for the design, simulation, and measurement of a microstrip patch antenna operating at 2.4 GHz. The project was developed using **AWR Design Environment** and verified through physical measurements in a laboratory environment.

## Project Overview

The main objective was to design a patch antenna with a $50\Omega$ microstrip line feed, optimized for a center frequency of **2.4 GHz** and maximum impedance matching.

### Design Specifications
* **Center Frequency:** 2.4 GHz
* **Substrate Permittivity ($\varepsilon_r$):** 2.6
* **Patch Dimensions:** $40 \times 40$ mm (approx. optimized from theoretical ~39mm)
* **Feed:** Coaxial probe / Microstrip line

## Methodology

1.  **Analytical Calculation:** Initial dimensions determined using transmission line model equations.
2.  **Simulation (AWR):**
    * Modeling the radiator and feed line.
    * Tuning dimensions to achieve $S_{11} < -10$ dB at target frequency.
    * Analysis of Voltage Standing Wave Ratio (VSWR).
3.  **Fabrication & Measurement:**
    * The antenna was manufactured and tested in an anechoic chamber.
    * **Radiation Pattern:** Measured at 2.2 GHz and 2.5 GHz to verify directional characteristics.

## Repository Contents

* `docs/Microstrip_Antenna_Report.pdf` - Full engineering report containing theoretical calculations, AWR simulation graphs ($S_{11}$, VSWR), and measurement results.

## Authors and Context

* **Authors:**
    * Filip Żurek
    * Dawid Makowski
    * Paweł Urban
* **Institution:** AGH University of Krakow
* **Faculty:** Faculty of Computer Science, Electronics and Telecommunications
* **Field of Study:** Electronics and Telecommunications
* **Course:** Microwave Techniques, Antenna Systems and Radio Wave Propagation

## License

This software is distributed under the MIT License. Refer to the [LICENSE](LICENSE) file for the full text.

---
*AGH University of Krakow - Microwave Techniques Course Project 2024*