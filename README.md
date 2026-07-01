# stability-lobe-diagram-for-turning-and-milling-application
The simulation models and algorithms in this repository are developed based on the methodologies presented in the textbook Machining Dynamics by Tony L. Schmitz.

# Machining Stability Lobe Diagram (SLD) Simulation

This repository contains Jupyter Notebook (`.ipynb`) simulation scripts for analyzing and constructing **Stability Lobe Diagrams (SLD)** for **Milling** and **Turning** machining processes. This project aims to assist engineers and researchers in determining optimal cutting parameters (such as axial depth of cut and spindle speed) to prevent chatter (unstable vibration) phenomena.

## 📌 Table of Contents
- [Key Features](#-key-features)
- [Repository Structure](#-repository-structure)
- [File Descriptions](#-file-descriptions)
- [Prerequisites & Dependencies](#-prerequisites--dependencies)
- [Usage Instructions](#-usage-instructions)
- [Theoretical Background](#-theoretical-background)
- [References](#-references)

---

## 🚀 Key Features
* **Milling Stability Analysis**: Calculates the average cutting angle ($\theta_{avg}$) for up-milling, down-milling, and slotting slotting configurations.
* **SLD Visualization**: Automatically plots the critical axial depth of cut ($b_{lim}$) against spindle speed ($n$) using the Frequency Response Function (FRF).
* **Turning Stability Analysis**: Provides time-domain dynamic simulations of single-point turning operations, validating analytical solutions against real-time simulation results ($F_{sim}$ vs $F_{m\_ana}$ and $y_{sim}$ vs $y_{m\_ana}$).

---

## 📂 Repository Structure
```text
├── Milling Stability Lobe.ipynb   # SLD simulation & plotting for Milling processes
├── Turning Stability Lobe.ipynb   # Dynamic analysis & validation for Turning processes
└── README.md                      # Project documentation


