# Quantum Computing Research Portfolio

**Asmeeta Prakash Sayaji** · asmitasayaji21@gmail.com · [Download CV](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Asmeeta_Sayaji_CV_Quantum_Computing.pdf) · [Research Portfolio](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Asmeeta_Sayaji_Research_Portfolio_2026.pdf)

Ahmedabad, India · Target: ETH Zürich Quantum Information Group (Prof. Renato Renner, Prof. Juan Carrasquilla, Prof. David Steurer, Prof. Matthias Troyer)

---

## 📋 Overview

This repository showcases my independent research in quantum information theory, with a focus on noise analysis, verification protocols, and quantum advantage certification. The work bridges theoretical quantum information concepts with hardware-informed modeling, leveraging my professional experience in cryogenic microwave engineering at ISRO.

The portfolio demonstrates a progression from fundamental quantum algorithms to advanced research topics directly relevant to superconducting quantum computation, particularly in the context of verification complexity and noise-adapted advantage thresholds.

**Key Research Outcomes:**
- **>90% leakage suppression** via DRAG pulse optimization
- **≈20% fidelity improvement** via zero-noise extrapolation
- **Analytical bounds** for verification complexity under T₁/T₂ noise

---

## 🎯 Research Focus Areas

- **Noise-Induced Classical Simulability:** Analytical bounds and simulations for quantum-to-classical transitions
- **Verification Complexity Scaling:** Sample complexity analysis under realistic noise models
- **Hardware-Informed Noise Modeling:** Translating experimental metrics (T₁, T₂) into quantum channel parameters
- **Leakage-Aware Quantum Control:** DRAG pulse optimization for transmon qubits

---

## 📁 Research Project Structure

The repository is organized to reflect a systematic research approach:

### 1) Foundations & Benchmarking
- `01_bell_states_entanglement.ipynb` — Bell state generation and entanglement verification
- `02_statevector_simulation.ipynb` — Noise-free circuit simulation for algorithm benchmarking

### 2) Noise Modeling & Decoherence
- `03_depolarizing_noise_analysis.ipynb` — Bell-state decay under generic depolarizing noise
- `04_superconducting_noise_channels.ipynb` — Realistic T₁/T₂/depolarizing channels for transmon qubits
- `05_composite_noise_simulation.ipynb` — Multi-channel noise effects on verification protocols

### 3) Quantum Advantage Verification
- `06_grover_verification.ipynb` — 2-qubit Grover search with verification overhead analysis
- `07_deutsch_jozsa_advantage.ipynb` — n=3 Deutsch–Jozsa algorithm demonstrating deterministic quantum advantage
- `08_verification_sample_complexity.ipynb` — Sample complexity scaling under various noise models

### 4) Advanced Research: Control & Simulation
- `09_lindblad_qubit_dynamics.ipynb` — Non-unitary dynamics of driven transmons using Lindblad master equation (QuTiP)
- `10_drag_pulse_optimization.ipynb` — DRAG pulse design for |1⟩→|2⟩ leakage suppression (**>90% achieved**)
- `11_noise_bench_qc/` — Structured-noise verification benchmarking suite
- `12_lindblad_sim/` — Non-Markovian and leakage-aware simulation toolkit

---

## 🛠️ Technical Implementation

### Software Tools Developed

| Tool | Description | Key Result |
| :--- | :---------- | :--------- |
| **Noise-Bench QC** | Verification benchmarking under structured noise | Systematic noise characterization |
| **Lindblad-Sim** | Non-Markovian simulation toolkit | Open system dynamics simulation |
| **ZNE Toolkit** | Zero-noise extrapolation framework | **≈20% fidelity improvement** |
| **DRAG Pulse Optimizer** | Adaptive pulse design for leakage suppression | **>90% leakage suppression** |

### Technical Stack

- **Quantum Frameworks:** Qiskit (Terra, Aer, Pulse), QuTiP, OpenQASM
- **Programming:** Python (NumPy, SciPy, Matplotlib, scikit-learn)
- **Quantum Theory:** Lindbladian models, smooth entropies, quantum channel divergences, resource theories
- **Mathematics:** Linear algebra, probability, information theory, optimization

### Hardware Relevance

Professional experience at ISRO with:
- Cryogenic systems (4 K) and microwave component characterization
- VNA S-parameter analysis and stability metrics (T₁, T₂, phase noise)
- Low-noise amplifier characterization for quantum readout systems

---

## 📊 Key Research Contributions

| Contribution | Description |
| :----------- | :---------- |
| **Analytical Bounds** | Derived verification-complexity scaling under T₁/T₂ noise |
| **Simulation Tools** | Developed open-source tools for noise-aware quantum circuit analysis |
| **Hardware Translation** | Bridged experimental characterization data with quantum noise models |
| **Verification Insights** | Identified noise thresholds for efficient classical simulability |
| **Leakage Suppression** | Achieved >90% |1⟩→|2⟩ leakage reduction via DRAG optimization |
| **Error Mitigation** | Demonstrated ≈20% fidelity improvement via ZNE |

---

## 🔬 Research Alignment with ETH Zürich

This work directly supports my PhD application to ETH Zürich, targeting research with:

- **Prof. Renato Renner** — Quantum information theory, smooth entropies, verification complexity
- **Prof. Juan Carrasquilla** — Quantum machine learning, quantum many-body physics
- **Prof. David Steurer** — Complexity theory, hardness of approximation
- **Prof. Matthias Troyer** — Quantum advantage, computational limits of near-term devices

**Focus areas:**
- Verification complexity of quantum computations under realistic noise
- Practical quantum advantage certification in NISQ devices
- Resource theories for noisy quantum computation
- Classical simulability thresholds and noise-adapted advantage

---

## 📄 Documents

| Document | Link |
| :------- | :--- |
| **CV** | [Asmeeta_Sayaji_CV_Quantum_Computing.pdf](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Asmeeta_Sayaji_CV_Quantum_Computing.pdf) |
| **Research Portfolio** | [Asmeeta_Sayaji_Research_Portfolio_2026.pdf](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Asmeeta_Sayaji_Research_Portfolio_2026.pdf) |

---

## ⚙️ Setup and Installation

```bash
# Clone repository
git clone https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace.git
cd ETH_Qiskit_Workspace

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# For QuTiP simulations (additional installation if needed)
# pip install qutip
