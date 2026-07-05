# Quantum Computing Research Portfolio

**Asmeeta Prakash Sayaji**  
Ahmedabad, India  
[asmitasayaji21@gmail.com](mailto:asmitasayaji21@gmail.com)  
[ETH_Qiskit_Workspace](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace)

---

## Overview

This repository showcases my independent research in quantum information theory, with a focus on noise analysis, verification protocols, and quantum advantage certification. The work bridges theoretical quantum information concepts with hardware-informed modeling, leveraging my professional experience in cryogenic microwave engineering at ISRO.

The portfolio demonstrates a progression from fundamental quantum algorithms to advanced research topics directly relevant to superconducting quantum computation, particularly in the context of verification complexity and noise-adapted advantage thresholds.

### Key Research Outcomes
- >90% leakage suppression via DRAG pulse optimization
- ~20% fidelity improvement via zero-noise extrapolation
- Analytical bounds for verification complexity under T1/T2 noise
- Identification of noise-triggered classical simulability transitions
- AI-driven quantum error mitigation optimization
- Hybrid quantum-classical classification models

---

## Documents

## CV

## CV

<object data="https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Sayaji_Asmeeta_CV.pdf" type="application/pdf" width="100%" height="600px">
    <p>PDF cannot be displayed. <a href="https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Sayaji_Asmeeta_CV.pdf">Download PDF</a></p>
</object>

---

## Research Portfolio

<object data="https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Quantum_Computing_Research_Portfolio.pdf" type="application/pdf" width="100%" height="600px">
    <p>PDF cannot be displayed. <a href="https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Quantum_Computing_Research_Portfolio.pdf">Download PDF</a></p>
</object>

---

## Research Focus Areas

| Focus Area | Description |
|------------|-------------|
| **Noise-Induced Classical Simulability** | Analytical bounds and simulations for quantum-to-classical transitions |
| **Verification Complexity Scaling** | Sample complexity analysis under realistic noise models |
| **Hardware-Informed Noise Modeling** | Translating experimental metrics (T1, T2) into quantum channel parameters |
| **Leakage-Aware Quantum Control** | DRAG pulse optimization for transmon qubits |
| **AI for Quantum Computing** | Machine learning for error mitigation, quantum algorithm optimization, hybrid models |

---

## Research Project Structure

### 1. Foundations & Benchmarking

| Notebook | Description |
|----------|-------------|
| `01_bell_states_entanglement.ipynb` | Bell state generation and entanglement verification |
| `02_statevector_simulation.ipynb` | Noise-free circuit simulation for algorithm benchmarking |

### 2. Noise Modeling & Decoherence

| Notebook | Description |
|----------|-------------|
| `03_depolarizing_noise_analysis.ipynb` | Bell-state decay under generic depolarizing noise |
| `04_superconducting_noise_channels.ipynb` | Realistic T1/T2/depolarizing channels for transmon qubits |
| `05_composite_noise_simulation.ipynb` | Multi-channel noise effects on verification protocols |

### 3. Quantum Advantage Verification

| Notebook | Description |
|----------|-------------|
| `06_grover_verification.ipynb` | 2-qubit Grover search with verification overhead analysis |
| `07_deutsch_jozsa_advantage.ipynb` | n=3 Deutsch–Jozsa algorithm demonstrating deterministic quantum advantage |
| `08_verification_sample_complexity.ipynb` | Sample complexity scaling under various noise models |

### 4. Advanced Research: Control & Simulation

| Notebook | Description |
|----------|-------------|
| `09_lindblad_qubit_dynamics.ipynb` | Non-unitary dynamics of driven transmons using Lindblad master equation (QuTiP) |
| `10_drag_pulse_optimization.ipynb` | DRAG pulse design for |1⟩→|2⟩ leakage suppression (>90% achieved) |
| `11_noise_bench_qc/` | Structured-noise verification benchmarking suite |
| `12_lindblad_sim/` | Non-Markovian and leakage-aware simulation toolkit |

### 5. AI & Quantum Computing (New)

| Notebook | Description |
|----------|-------------|
| `13_ai_error_mitigation/` | AI-driven Zero-Noise Extrapolation optimization |
| `14_hybrid_qml/` | Hybrid quantum-classical machine learning frameworks |
| `15_qaoo/` | QAOA optimization with quantum-enhanced embeddings |

---

## Full Notebook

The complete notebook `ETH_Qiskit_Simulations_AI.ipynb` consolidates all simulations, including:

- **Programs 1-6:** Bell states, Grover, Deutsch–Jozsa, superconducting noise
- **Program 7:** DRAG pulse optimization (leakage suppression)
- **Program 8:** Open quantum systems (QuTiP, Lindblad)
- **Program 9:** AI-assisted quantum error mitigation
- **Program 10:** Hybrid quantum-classical classification

---

## Technical Implementation

### Software Tools Developed

| Tool | Description | Key Result |
|------|-------------|------------|
| **Noise-Bench QC** | Verification benchmarking under structured noise | Systematic noise characterization |
| **Lindblad-Sim** | Non-Markovian simulation toolkit | Open system dynamics simulation |
| **ZNE Toolkit** | Zero-noise extrapolation framework | ~20% fidelity improvement |
| **DRAG Pulse Optimizer** | Adaptive pulse design for leakage suppression | >90% leakage suppression |
| **AI-Error Mitigation** | Neural network-driven error mitigation optimization | Automated ZNE parameter tuning |
| **Hybrid-QML** | Hybrid quantum-classical ML framework | Quantum-enhanced feature extraction |

### Technical Stack

| Category | Tools |
|----------|-------|
| **Quantum Frameworks** | Qiskit (Terra, Aer, Pulse), QuTiP, OpenQASM |
| **Programming** | Python (NumPy, SciPy, Matplotlib, scikit-learn) |
| **AI/ML** | TensorFlow, PyTorch, Scikit-Learn |
| **Quantum Theory** | Lindbladian models, smooth entropies, quantum channel divergences, resource theories |
| **Mathematics** | Linear algebra, probability, information theory, optimization |

### Hardware Relevance

Professional experience at ISRO with:
- Cryogenic systems (4K) and microwave component characterization
- VNA S-parameter analysis and stability metrics (T1, T2, phase noise)
- Low-noise amplifier characterization for quantum readout systems

---

## Key Research Contributions

| Contribution | Description |
|--------------|-------------|
| **Analytical Bounds** | Derived verification-complexity scaling under T1/T2 noise |
| **Simulation Tools** | Developed open-source tools for noise-aware quantum circuit analysis |
| **Hardware Translation** | Bridged experimental characterization data with quantum noise models |
| **Verification Insights** | Identified noise thresholds for efficient classical simulability |
| **Leakage Suppression** | Achieved >90% suppression via DRAG pulse optimization |
| **Error Mitigation** | Demonstrated ~20% fidelity improvement via ZNE |
| **AI-Error Mitigation** | Neural network-driven ZNE parameter optimization |
| **Hybrid-QML** | Quantum-enhanced feature extraction for classification |

---

## Research Alignment with ETH Zürich

This work directly supports my PhD applications to ETH Zürich, targeting research with:

| Position | Supervisor | Research Area |
|----------|------------|---------------|
| **Dominik Hangleiter** | Prof. Dominik Hangleiter | Quantum complexity, verification, noisy quantum systems |
| **ETH + IBM Research** | Dr. David Sutter, Prof. Renato Renner, Dr. Elisa Bäumer, Dr. Christophe Piveteau | Quantum information theory, error mitigation, foundations |
| **AI × Quantum Computing** | Dr. Stefan Woerner, Prof. Juan Carrasquilla | AI-driven quantum algorithms, optimization, hybrid models |

### Focus Areas:
- Verification complexity of quantum computations under realistic noise
- Practical quantum advantage certification in NISQ devices
- Resource theories for noisy quantum computation
- Classical simulability thresholds and noise-adapted advantage
- AI-driven quantum error mitigation and optimization

---

## Setup and Installation

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
pip install qutip
