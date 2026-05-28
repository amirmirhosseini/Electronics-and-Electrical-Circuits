# Electric Circuits I - Computer Assignment (Biomedical Signal Processing & Indicator System)

This repository contains the simulation files and technical report for the **Electric Circuits I** computer assignment at the **University of Tehran** (Winter 2024).

## Project Overview & System Phases:
* **Part 1 (Op-Amp Fundamentals):** Design and simulation of basic analog blocks including amplifiers, buffers, integrators, and differentiators.
* **Part 2 - Phase 1 (Biomedical Noise Cancellation):** Simulating a medical device monitoring vital body signals, where a high-amplitude **50Hz power-line noise** is filtered out from the main biomedical signal using an active **High-Pass Filter (HPF)**.
* **Part 2 - Phase 2 (Signal Rectification & Delayed Alert Logic):** Converting the filtered AC signal into a stable DC voltage (representing a Glucometer/Sensor output) using a half-wave rectifier, monitoring thresholds with an Op-Amp **Window Comparator**, and implementing a custom **RC Delay Circuit** to trigger safety LEDs only after a sustained 9-second threshold violation.

*All systems are fully simulated and analyzed using **NI Multisim**.*
