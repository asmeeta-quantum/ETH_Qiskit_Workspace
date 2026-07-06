# Quantum Computing Research Portfolio — AI × Optimization

**Asmeeta Prakash Sayaji**  
Ahmedabad, India  
[asmitasayaji21@gmail.com](mailto:asmitasayaji21@gmail.com)  
[ETH_Qiskit_Workspace](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace)

---

## Overview

This repository showcases my independent research across three interconnected domains: **Quantum Foundations**, **Quantum + AI**, and **Quantum Optimization**. The work bridges theoretical quantum information concepts with hardware-informed modeling, AI-driven quantum error mitigation, and optimization algorithms.

### Key Research Outcomes

| Area | Achievement |
|------|-------------|
| **Quantum Foundations** | Bell states, Grover, Deutsch-Jozsa, superconducting qubit noise, DRAG pulse, open quantum systems |
| **AI + Quantum** | Neural-network-assisted ZNE, hybrid quantum-classical classification |
| **Quantum Optimization** | QAOA for Max-Cut, RL for QAOA parameter discovery, quantum sampling for classical solvers |

---

## Programs (Full List)

### Quantum Foundations (Programs 1-8)

| Program | Title | Description |
|---------|-------|-------------|
| 1 | Bell State with Measurement Sampling | Bell state generation and entanglement verification |
| 2 | Ideal Statevector Simulation | Noise-free circuit simulation for algorithm benchmarking |
| 3 | Noisy Bell State Simulation | Bell-state decay under depolarizing noise |
| 4 | Grover's Algorithm (2-qubit) | 2-qubit Grover search with verification overhead analysis |
| 5 | Deutsch–Jozsa Algorithm (n=3) | Deterministic quantum advantage demonstration |
| 6 | Superconducting Qubit Noise Simulation | T1/T2/depolarizing channels for transmon qubits |
| 7 | DRAG Pulse Design | Leakage suppression for |1⟩→|2⟩ transitions (>90% achieved) |
| 8 | Open Quantum Systems (QuTiP) | Non-unitary dynamics using Lindblad master equation |

### AI + Quantum Computing (Programs 9-10)

| Program | Title | Description |
|---------|-------|-------------|
| 9 | AI-Assisted Quantum Error Mitigation | Neural network (MLPRegressor) for ZNE parameter optimization |
| 10 | Hybrid Quantum-Classical Classification | Random Forest + Quantum Kernel classification |

### AI + Quantum Optimization (Programs 11-13)

| Program | Title | Description |
|---------|-------|-------------|
| 11 | QAOA for Max-Cut | Quantum Approximate Optimization Algorithm with parameter learning |
| 12 | AI-Driven QAOA with RL | Reinforcement learning for QAOA parameter discovery |
| 13 | Quantum Sampling for Classical Solvers | Generating quantum samples to warm-start classical AI solvers |

---

## Research Focus Areas

| Focus Area | Description |
|------------|-------------|
| **Noise-Induced Classical Simulability** | Analytical bounds and simulations for quantum-to-classical transitions |
| **Verification Complexity Scaling** | Sample complexity analysis under realistic noise models |
| **Hardware-Informed Noise Modeling** | Translating experimental metrics (T1, T2) into quantum channel parameters |
| **Leakage-Aware Quantum Control** | DRAG pulse optimization for transmon qubits |
| **AI for Quantum Computing** | Machine learning for error mitigation, quantum algorithm discovery, hybrid models |
| **Quantum Optimization** | QAOA, reinforcement learning for circuit design, quantum sampling |

---

## Documents

| Document | Link |
|----------|------|
| **CV** | [Download PDF](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Sayaji_Asmeeta_CV.pdf) |
| **Research Portfolio** | [Download PDF](https://github.com/asmeeta-quantum/ETH_Qiskit_Workspace/raw/main/Quantum_Computing_Research_Portfolio.pdf) |

> 💡 **Note:** If the PDF doesn't render in your browser, click the link above and select "Raw" or download the file directly.

---

## Technical Implementation

### Software Tools Developed

| Tool | Description | Key Result |
|------|-------------|------------|
| **Noise-Bench QC** | Verification benchmarking under structured noise | Systematic noise characterization |
| **Lindblad-Sim** | Non-Markovian and leakage-aware simulation toolkit | Open system dynamics simulation |
| **ZNE Toolkit** | Zero-Noise Extrapolation framework | ~20% fidelity improvement |
| **DRAG Pulse Optimizer** | Adaptive pulse design for leakage suppression | >90% leakage suppression |
| **AI-Error Mitigation** | Neural network-driven error mitigation optimization | Automated ZNE parameter tuning |
| **Hybrid-QML** | Hybrid quantum-classical ML framework | Quantum-enhanced feature extraction |
| **QAOA-Optimizer** | Parameter learning for quantum optimization | Learned optimal γ and β |
| **RL-QAOA** | Reinforcement learning for circuit discovery | Parameter selection via Q-learning |

### Technical Stack

| Category | Tools |
|----------|-------|
| **Quantum Frameworks** | Qiskit (Terra, Aer, Pulse), QuTiP, OpenQASM |
| **Programming** | Python (NumPy, SciPy, Matplotlib, scikit-learn) |
| **AI/ML** | TensorFlow, PyTorch, Scikit-Learn |
| **Quantum Optimization** | QAOA, COBYLA, SPSA, Reinforcement Learning |
| **Quantum Theory** | Lindbladian models, smooth entropies, quantum channel divergences, resource theories |
| **Mathematics** | Linear algebra, probability, information theory, optimization |

### Hardware Relevance

Professional experience at ISRO with:
- Cryogenic systems (4K) and microwave component characterization
- VNA S-parameter analysis and stability metrics (T1, T2, phase noise)
- Low-noise amplifier characterization for quantum readout systems

---

## Research Alignment with ETH Zürich

This work supports PhD applications to ETH Zürich across three positions:

| Position | Supervisor(s) | Research Area |
|----------|---------------|---------------|
| **Dominik Hangleiter** | Prof. Dominik Hangleiter | Quantum complexity, verification, noisy quantum systems |
| **ETH + IBM Research** | Dr. David Sutter, Prof. Renato Renner, Dr. Elisa Bäumer, Dr. Christophe Piveteau | Quantum information theory, error mitigation, foundations |
| **AI × Quantum Computing** | Dr. Stefan Woerner, Prof. Juan Carrasquilla | AI-driven quantum algorithms, optimization, hybrid models |

### Focus Areas:
- Verification complexity of quantum computations under realistic noise
- Practical quantum advantage certification in NISQ devices
- Resource theories for noisy quantum computation
- Classical simulability thresholds and noise-adapted advantage
- AI-driven quantum error mitigation and optimization
- Quantum optimization with AI-assisted parameter learning

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

# For QAOA and RL programs
pip install rustworkx scipy
