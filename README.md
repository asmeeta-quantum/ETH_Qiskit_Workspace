# Quantum Computing Research Portfolio
**Asmeeta Prakash Sayaji** · `asmitasayaji21@gmail.com` · [Download CV](Sayaji_Asmeeta_CV_Quantum_Researcher.pdf) · [Research Portfolio](Sayaji_Asmeeta_Research_Portfolio.pdf)

**Ahmedabad, India** · **Target: ETH Zürich Quantum Information Group (Prof. Dominik Hangleiter)**

---

## 📋 Overview

This repository showcases my independent research in **quantum information theory**, with a focus on **noise analysis, verification protocols, and quantum advantage certification**. The work bridges theoretical quantum information concepts with hardware-informed modeling, leveraging my professional experience in cryogenic microwave engineering at ISRO.

The portfolio demonstrates a progression from fundamental quantum algorithms to advanced research topics directly relevant to superconducting quantum computation, particularly in the context of **verification complexity** and **noise-adapted advantage thresholds**.

## 🎯 Research Focus Areas

- **Noise-Induced Classical Simulability**: Analytical bounds and simulations for quantum-to-classical transitions
- **Verification Complexity Scaling**: Sample complexity analysis under realistic noise models
- **Hardware-Informed Noise Modeling**: Translating experimental metrics (T₁, T₂) into quantum channel parameters
- **Leakage-Aware Quantum Control**: DRAG pulse optimization for transmon qubits

## 📁 Research Project Structure

The repository is organized to reflect a systematic research approach:

### **1) Foundations & Benchmarking**
- `01_bell_states_entanglement.ipynb` — Bell state generation and entanglement verification
- `02_statevector_simulation.ipynb` — Noise-free circuit simulation for algorithm benchmarking

### **2) Noise Modeling & Decoherence**
- `03_depolarizing_noise_analysis.ipynb` — Bell-state decay under generic depolarizing noise
- `04_superconducting_noise_channels.ipynb` — Realistic T₁/T₂/depolarizing channels for transmon qubits
- `05_composite_noise_simulation.ipynb` — Multi-channel noise effects on verification protocols

### **3) Quantum Advantage Verification**
- `06_grover_verification.ipynb` — 2-qubit Grover search with verification overhead analysis
- `07_deutsch_jozsa_advantage.ipynb` — n=3 Deutsch–Jozsa algorithm demonstrating deterministic quantum advantage
- `08_verification_sample_complexity.ipynb` — Sample complexity scaling under various noise models

### **4) Advanced Research: Control & Simulation**
- `09_lindblad_qubit_dynamics.ipynb` — Non-unitary dynamics of driven transmons using Lindblad master equation (QuTiP)
- `10_drag_pulse_optimization.ipynb` — DRAG pulse design for |1⟩→|2⟩ leakage suppression (>90% achieved)
- `11_noise_bench_qc/` — Structured-noise verification benchmarking suite
- `12_lindblad_sim/` — Non-Markovian and leakage-aware simulation toolkit

## 🛠️ Technical Implementation

### **Software Tools Developed**
- **Noise-Bench QC**: Verification benchmarking under structured noise
- **Lindblad-Sim**: Non-Markovian simulation toolkit
- **ZNE Toolkit**: Zero-noise extrapolation framework (≈20% fidelity improvement)
- **DRAG Pulse Optimizer**: Adaptive pulse design for leakage suppression

### **Technical Stack**
**Quantum Frameworks:** Qiskit (Terra, Aer, Pulse), QuTiP, OpenQASM  
**Programming:** Python (NumPy, SciPy, Matplotlib, scikit-learn)  
**Quantum Theory:** Lindbladian models, smooth entropies, quantum channel divergences, resource theories  
**Mathematics:** Linear algebra, probability, information theory, optimization

### **Hardware Relevance**
Professional experience at ISRO with:
- Cryogenic systems (4 K) and microwave component characterization
- VNA S-parameter analysis and stability metrics (T₁, T₂, phase noise)
- Low-noise amplifier characterization for quantum readout systems

## 📊 Key Research Contributions

1. **Analytical Bounds**: Derived verification-complexity scaling under T₁/T₂ noise
2. **Simulation Tools**: Developed open-source tools for noise-aware quantum circuit analysis
3. **Hardware Translation**: Bridged experimental characterization data with quantum noise models
4. **Verification Insights**: Identified noise thresholds for efficient classical simulability

## 🔬 Research Alignment with ETH Zürich

This work directly supports my PhD application to work with **Prof. Dominik Hangleiter** at ETH Zürich, focusing on:

- **Verification complexity** of quantum computations under realistic noise
- **Practical quantum advantage** certification in NISQ devices
- **Resource theories** for noisy quantum computation
- **Classical simulability** thresholds and noise-adapted advantage

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