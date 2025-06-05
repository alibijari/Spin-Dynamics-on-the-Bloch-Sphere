# 🌀 Bloch Vector Dynamics & Rabi Oscillations for Spin-1/2 System

A modern toolkit for **analytic derivation**, **numerical simulation**, and **visualization** of the quantum dynamics of a single spin-1/2 particle (two-level system) in a static magnetic field with a resonant or detuned RF field.  
This package is ideal for students and researchers in quantum mechanics, NMR/EPR, quantum optics, and quantum information science.

---

## 🌟 Project Highlights

- **Self-contained analytical derivation:**  
  Step-by-step calculation of the time-dependent expectation values $\langle S_x(t) \rangle$, $\langle S_y(t) \rangle$, $\langle S_z(t) \rangle$ for a spin-1/2 in combined static and RF magnetic fields, including *lab frame* and *rotating frame* analysis.
- **Python simulation code:**  
  Ready-to-run Python scripts for simulating and plotting the Bloch vector trajectory, Rabi oscillations, detuning, and more.
- **Interactive notebook:**  
  (Optional) Jupyter notebook for parameter sweeps and real-time visualization on the Bloch sphere.

---

## 🧑‍🔬 Physical Model

The quantum Hamiltonian for a spin-1/2 in static and RF fields:

$$
\hat{H} = \frac{\hbar}{2}\left[\omega_0 \sigma_z + g\left(\sigma_x \cos\omega t + \sigma_y \sin\omega t\right)\right]
$$

- **$\omega_0$**: Larmor frequency (proportional to static field $B_z$)
- **$\omega$**: RF drive frequency
- **$g$**: RF coupling (proportional to RF field amplitude $B_1$)
- **$\sigma_x, \sigma_y, \sigma_z$**: Pauli matrices

This model describes Rabi oscillations, detuning, and the evolution of the Bloch vector.

---

## 📁 Repository Contents

| File / Folder         | Description                                                                                        |
|-----------------------|----------------------------------------------------------------------------------------------------|
| `spin.pdf`            | Full analytic derivation (clean and typeset): time evolution, expectation values, Rabi oscillations |
| `spin_2.pdf`          | Supplementary handwritten theoretical notes and preliminary proofs                                  |
| `blochvector.ipynb`   | (Optional) Jupyter notebook for interactive visualization and parameter exploration                |

---

## 🚀 How to Run

1. **Review the theory:**  
   - Open `spin.pdf` for detailed analytic derivations  
   - See `spin_2.pdf` for hand-written preliminary notes

2. **Run the simulation code:**  
   - Use the scripts in `blochvector/` to reproduce Bloch vector and Rabi oscillation plots  
   - Or use the notebook for interactive demos

   ```bash
   pip install numpy matplotlib jupyter
   # Run Python scripts or open the notebook in JupyterLab/Notebook
