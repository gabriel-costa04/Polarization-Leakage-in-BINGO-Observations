# 📡 Polarization Leakage Characterization in the BINGO Radio Telescope

## ✨ Overview

This repository contains the work and results for a Master's project focused on characterizing and mitigating **polarization leakage** in the **BINGO (BAO from Integrated Neutral Gas Observations) Radio Telescope**.

The $21\text{cm}$ line emission from neutral hydrogen ($\text{HI}$) is a powerful and complementary cosmological probe, offering insights into the large-scale structure of the Universe and helping to constrain models of its accelerated expansion.  However, observing this faint signal is done indirectly through integrated observations, which demands precise instrumental control over various contaminants and calibration effects.

A critical contamination source is **polarization leakage**. This instrumental effect introduces spurious signals into the total intensity parameter (Stokes $I$), making it difficult to separate the cosmological $\text{HI}$ signal from astrophysical foreground emissions. This limitation is a major hurdle for $21\text{cm}$ experiments like BINGO, a Brazilian-led radio telescope designed to detect Baryon Acoustic Oscillations (BAOs) via $\text{HI}$ emission.

---

## 🎯 Project Goals

This project aims to address, estimate, and characterize the polarization leakage in BINGO observations, considering its specific optical design. Key objectives include:

* **Simulation:** Performing computational simulations using the **GRASP** software package to model electromagnetic radiation propagation within BINGO's complex optical system.
* **Polarization Analysis:** Calculating the polarization parameters (Stokes parameters $I, Q, U, V$) at various points in the system.
* **Mueller Matrix Determination:** Determining the **Mueller Matrix** associated with the BINGO optical system, which precisely quantifies how different polarization states transform as they pass through the optics. 

---

## 🛠️ Methodology

The core of the project involves high-fidelity electromagnetic simulations:

1.  **Optical Model:** Creating a detailed model of the BINGO optical design within GRASP, including the primary and secondary reflectors.
2.  **Field Propagation:** Simulating the propagation of polarized electromagnetic waves from the sky (representing the input signal and foregrounds) through the telescope optics.
3.  **Leakage Estimation:** Analyzing the resulting Stokes parameters at the receiver plane to quantify the magnitude of spurious intensity (Stokes $I$) created by the transformation of incident polarized signals (Stokes $Q$ and $U$).
4.  **Characterization:** Using the simulation results to construct and analyze the Mueller Matrix, which provides a complete description of the system's polarization response, including the exact terms responsible for leakage.

---

## 📈 Expected Outcomes

The successful completion of this project is expected to yield:

* **Detailed Understanding:** A comprehensive understanding of the origin and magnitude of polarization leakage within the BINGO telescope.
* **Mitigation Strategies:** The development of specific strategies for controlling or mitigating this instrumental effect (e.g., suggesting tighter manufacturing tolerances or improved calibration schemes).
* **Enhanced Data Quality:** A significant contribution to the robustness of cosmological observations performed by BINGO, strengthening its capability to explore the large-scale structure of the Universe.

---

## 🔬 Related Information

* **BINGO Radio Telescope:** https://bingotelescope.org/
* **GRASP Software:** Software used for the physical optics and diffraction analysis.
* **Relevant Physics:** Radio Astronomy, $\text{HI}$ Cosmology, Baryon Acoustic Oscillations (BAO), Polarization Optics, Stokes Parameters, Mueller Matrices.

---

## 🤝 Contact

For questions or collaborations, please contact Gabriel Costa at gabrielfisi.co@usp.br.

This project is part of the Master's program in Instituto de Física da USP.
