# Photonic Computing Core & Chip Physical Fingerprint (Chip-DNA) Database

[English] | [简体中文](README_zh.md)

[![License: CERN-OHL-S v2](https://img.shields.io/badge/Hardware_License-CERN--OHL--S_v2-blue.svg)](./LICENSE-HARDWARE)
[![License: LGPL v3](https://img.shields.io/badge/Software_License-LGPL_v3-green.svg)](./LICENSE-SOFTWARE)

---
## 📄 Technical Black Paper


---

## 🌟 Core Technical Highlights

1. **Pure Electrostatic Modulation Mechanism:**  
   Eliminates thermal phase-change delays and thermal dissipation overhead, achieving **GHz to THz** operational frequencies with near-zero static power dissipation.
2. **Sub-Wavelength Surface Plasmon Polariton (SPP) Localization:**  
   Compresses computing unit dimensions down to the **sub-micron/nanometer scale** (reducing footprint by 3–4 orders of magnitude compared to conventional silicon photonics), enabling ultra-high-density monolithic and heterogeneous integration.
3. **Beyond-Binary Architecture:**  
   Breaks the traditional binary (0/1) paradigm by implementing **multi-wavelength encoded multi-valued logic** and **analog arithmetic operations** (addition/subtraction/multiplication/division) enabled by non-linear optical frequency conversion (SFG/DFG) and saturable absorption.
4. **Flip-Chip Modular Heterointegration Process:**  
   Resolves the yield degradation and material fracturing bottlenecks typical in 2D material (Graphene/TMDs) transfer. The flip-chip configuration provides intrinsic environmental passivation without complex external hermetic packaging.
5. **Global Chip Physical Fingerprint (Chip-DNA) Public Registry:**  
   Maps and registers nanoscale intrinsic physical variations and fabrication defects to eradicate hardware supply chain risks. These unique physical features serve as keys for **Physical Unclonable Function (PUF)** hardware-rooted cryptographic authentication.

---

## 🗂️ Repository Branch Guide (Navigation)

* 📐 **Branch `[simulation-and-fabrication]`:**  
  Lumerical FDTD optical electromagnetic simulation models, micro-nano fabrication workflow specifications, and lithography mask layouts (GDSII).
* 💻 **Branch `[compiler-and-isa]`:**  
  Photonic Instruction Set Architecture (P-ISA) specifications, hardware decoders, and all-optical algorithmic compute drivers.
* 🛡️ **Branch `[chip-dna-database]`:**  
  Open-access attestation database and verification APIs for factory-calibrated commercial and research chip physical fingerprints (Chip-DNA).

---

## 🤝 Call for Contributors (Simulation / FDTD)

We are actively seeking collaborators passionate about nanophotonics, computational physics, and next-generation computer architectures:
* **FDTD / Electromagnetic Simulation:** Anyone proficient in **Ansys Lumerical (FDTD/MODE)** or **COMSOL Wave Optics** to help refine our optical cavity models, calculate LSPR enhancement factors, and optimize electric-field tuning spectra (No formal academic pedigree required—ability to deliver models is what matters).
* **Compilers & System Architecture:** Developers interested in mapping non-binary photonic logic to LLVM/MLIR frameworks.

*This is a community-driven, purely open-source exploration under CERN-OHL and LGPL protocols. All contributions and models are permanently open-access and co-credited.*

---

## ⚖️ Open Source License Declaration

This project adopts a dual-track open-source licensing model for hardware and software:

1. **Hardware Designs & Manufacturing Layouts:**  
   Licensed under the **[CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S v2)](./LICENSE-HARDWARE)**.
2. **Underlying Instruction Set, Drivers & Compiler Source Code:**  
   Licensed under the **[GNU Lesser General Public License v3.0 (GNU LGPL-3.0)](./LICENSE-SOFTWARE)**.
