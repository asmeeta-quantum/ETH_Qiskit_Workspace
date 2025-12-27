# **Quantum Computing Research Portfolio**
**Asmeeta Prakash Sayaji** · [asmitasayaji21@gmail.com](mailto:asmitasayaji21@gmail.com) · [Download CV](Sayaji_Asmeeta_CV_Quantum_Researcher.pdf) · [Research Portfolio](Research_Portfolio.pdf)

Ahmedabad, India

## Overview
This repository contains code and notebooks from my independent research in quantum computing, complementing my professional background in cryogenic microwave engineering at ISRO. It demonstrates a practical understanding of quantum algorithms, noise processes, and pulse-level control—directly relevant to experimental superconducting quantum computation.

> For a deeper discussion and critical analysis, see the formal **Research Portfolio** PDF linked above.

## Research Project Structure
The work progresses from foundations to advanced topics. Each notebook is self-contained and runnable.

### 1) Foundations of Quantum Circuits & Entanglement
- **`1a_bell_states.ipynb`** — Generation and measurement sampling of Bell states to study entanglement statistics.  
- **`1b_statevector_simulation.ipynb`** — Noise-free quantum circuit simulation for algorithm benchmarking.

### 2) Understanding Quantum Noise and Decoherence
- **`2a_depolarizing_noise.ipynb`** — Modeling Bell-state decay under generic depolarizing noise.  
- **`2b_superconducting_t1_t2_noise.ipynb`** — Realistic channels for transmon-like qubits (T₁, T₂, depolarizing).

### 3) Quantum Algorithm Implementation & Advantage
- **`3a_grover_2_qubit.ipynb`** — 2-qubit Grover search: oracle, diffusion, success probability.  
- **`3b_deutsch_jozsa_n3.ipynb`** — Deterministic quantum advantage via the n=3 Deutsch–Jozsa algorithm.

### 4) Advanced Research: Open Systems & Pulse-Level Control
- **`4a_lindblad_qubit_dynamics.ipynb`** — Non-unitary dynamics of a *driven* transmon using the **Lindblad** master equation in **QuTiP**.  
- **`4b_drag_pulse_design.ipynb`** — **DRAG** pulse design in Qiskit Pulse to suppress \|1⟩→\|2⟩ leakage in transmons.

## 🛠️ Technical Skills Demonstrated
- **Quantum Frameworks:** Qiskit (Terra, Aer, Pulse), OpenQASM, QuTiP  
- **Programming:** Python (NumPy, SciPy, Matplotlib)  
- **Quantum Concepts:** Quantum noise & decoherence (T₁, T₂), Lindblad master equation, pulse-level control (DRAG), transmon physics, algorithms (Grover, Deutsch–Jozsa)  
- **Hardware Relevance:** Experience with cryogenic systems (~4 K), VNA S-parameter analysis, and low-noise amplifier characterization at **ISRO**.

## ⚙️ Setup and Installation
To reproduce results locally:

```bash
# clone
git clone https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace.git
cd ETH_Qiskit_Workspace

# (recommended) create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# install dependencies
pip install -r requirements.txt
