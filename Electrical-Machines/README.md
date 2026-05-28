# Electrical Machines - Finite Element Analysis (FEA) of Magnetic Circuits

This repository contains the advanced simulations and electromagnetic analysis for the **Electrical Machines** course at the **University of Tehran**. The projects utilize **COMSOL Multiphysics (2D)** to perform Finite Element Analysis (FEA) on magnetic cores, solving Maxwell's equations numerically.(Winter 2025)

## Project Objectives & Simulation Core

Instead of basic analytical hand calculations, this project focuses on the visual and numerical evaluation of magnetic fields, core saturation, and the effects of air gaps in electrical machine cores.

### Core Simulation Tasks & Objectives:

* **Part 1: Linear & Non-linear Magnetic Circuits (Core Saturation Study)**
  * **Objective:** Investigating the B-H curve and magnetic behavior of different core materials.
  * **Analysis:** Simulating the core under a parametric sweep of excitation currents ($I_{test}$) using custom multi-turn coils ($N_{turns}$) to plot **Magnetic Flux Density ($B$)** and capture the exact point where the magnetic material transitions from a linear state into **saturation**.

* **Part 2: Magnetic Circuit with Air Gap (Fringing Effect & Reluctance Study)**
  * **Objective:** Analyzing the severe impact of introducing a 5mm air gap into a non-linear magnetic circuit.
  * **Analysis:** Evaluating how the air gap increases the total reluctance of the circuit, mapping the **Fringing Effect** (magnetic flux leaking outside the gap edges), and comparing the altered flux density curves against the solid core model.

* **Part 3: Multi-Coil Systems & Mutual Flux**
  * **Objective:** Simulating transformers and multi-winding machine topologies.
  * **Analysis:** Implementing two separate coils with independent current parameters to study mutual inductance, magnetic coupling, and flux path distributions inside the ferromagnetic core.

---

## Tools & Methods Used
* **Software:** COMSOL Multiphysics (AC/DC Module > Magnetic Fields `mf`)
* **Study Type:** Stationary & Parametric Sweeps
* **Key Visualizations Generated:** Magnetic Flux Density Surface Plots ($T$), Streamline Magnetic Vector Potential maps, and $B-I$ Convergence Plots.
