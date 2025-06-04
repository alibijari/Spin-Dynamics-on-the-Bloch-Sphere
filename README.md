# Bloch Vector Dynamics and Rabi Oscillations for a Spin-1/2 System

## Overview

This repository provides a comprehensive toolkit for the **analytic derivation, numerical simulation, and visualization** of the quantum dynamics of a single spin-1/2 particle (two-level system) in a static magnetic field with a resonant or detuned RF field.  
The package is useful for students and researchers in quantum mechanics, NMR/EPR, quantum optics, and related areas.

**Features:**
- Self-contained analytical derivation of time-dependent expectation values ⟨Sₓ(t)⟩, ⟨Sᵧ(t)⟩, ⟨S_z(t)⟩ (`spin.pdf`)
- Ready-to-run Python scripts for simulation and visualization of Bloch vector dynamics under various conditions
- (Optional) Jupyter notebook for interactive exploration

---

## Physical Model

The quantum Hamiltonian for a spin-1/2 in a static and RF field:

where:
- **ω₀**: Larmor frequency (proportional to static field B_z)
- **ω**: RF drive frequency
- **g**: RF coupling (proportional to RF field amplitude B₁)
- **σ_x, σ_y, σ_z**: Pauli matrices

This model describes Rabi oscillations, detuning effects, and the evolution of the Bloch vector.

---

## Repository Contents

- **spin.pdf**  
  *Detailed analytic derivation of Bloch vector expectation values and Rabi oscillations. Covers laboratory and rotating frames, operator definitions, and transformation formulas.*

- **blochvector**  
  *Python scripts for simulation and visualization:*  
    - Numerical solution of the time-dependent Schrödinger equation for a two-level system  
    - Simulation and plotting of ⟨Sₓ(t)⟩, ⟨Sᵧ(t)⟩, ⟨S_z(t)⟩, and optionally 3D Bloch sphere animation  
    - Easily customizable parameters for field strengths, detuning, and initial states

- **blochvector.ipynb** (optional)  
  *Jupyter notebook for interactive visualization and parameter exploration.*

---


