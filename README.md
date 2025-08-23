# Quantum Computing Research Portfolio

**Asmeeta Prakash Sayaji** | [Email](mailto:asmitasayaji21@gmail.com) | [CV](./Asmeeta_Quantum_CV.pdf) | Ahmedabad, India

This repository contains code and notebooks from my independent research in quantum computing, complementing my professional background in **cryogenic microwave engineering at ISRO**. It demonstrates a practical understanding of quantum algorithms, noise processes, and pulse-level control, directly relevant to experimental superconducting quantum computation.

---

## 📂 Project Portfolio

The projects are organized to reflect a progression from fundamental principles to advanced topics in quantum control and error mitigation.

### 1. Foundations of Quantum Circuits & Entanglement
- **Bell State Simulations:** Generated and sampled Bell states to study entanglement and measurement statistics.
- **Ideal Statevector Simulation:** Built noise-free quantum circuit simulations for benchmarking algorithms and validating outputs.

### 2. Understanding Quantum Noise and Decoherence
- **Noisy Circuit Simulation (Depolarizing Errors):** Modeled Bell state decoherence with depolarizing channels to analyze fidelity loss under generic quantum noise.
- **Superconducting Qubit Noise Simulation (`T₁`, `T₂`, Depolarizing`):`** Simulated realistic noise channels (relaxation, dephasing, depolarizing) to evaluate performance limitations of transmon-like qubits.

### 3. Quantum Algorithm Implementation & Advantage
- **Grover's Algorithm (2-qubit):** Implemented and analyzed a simplified Grover search circuit for proof-of-concept testing of amplitude amplification.
- **Deutsch-Jozsa Algorithm (n=3):** Demonstrated deterministic quantum advantage by implementing and testing the n=3 circuit, verifying its correctness in a single oracle query.

### 4. Advanced Research: Open Systems & Pulse-Level Control
- **Open Quantum Systems Simulation (`QuTiP`):** Modeled non-unitary dynamics of a driven transmon qubit using the Lindblad master equation, analyzing `T₁/T₂` decoherence effects on state fidelity.
- **Transmon Qubit Modeling & DRAG Pulse Design (`Qiskit Pulse`):** Investigated transmon properties (charge dispersion, anharmonicity) based on the Koch et al. model. Designed and simulated Derivative Removal by Adiabatic Gate (DRAG) pulses for leakage suppression in 2-qubit gates.
- **Quantum Error Mitigation (ZNE):** Benchmarked Grover's algorithm on IBM noisy simulators, applying Zero-Noise Extrapolation (ZNE) to enhance success probability from `~65%` to `≈85%`.

---

## 🛠️ Technical Skills Demonstrated

*   **Quantum Frameworks:** Qiskit (Terra, Aer, Pulse), OpenQASM, QuTiP
*   **Programming:** Python (NumPy, SciPy, Matplotlib, Pandas)
*   **Quantum Concepts:** Quantum Noise & Decoherence (`T₁`, `T₂`), Lindblad Master Equation, Quantum Error Mitigation (ZNE), Pulse-Level Control (DRAG), Transmon Qubits, Quantum Algorithms (Grover, Deutsch-Jozsa)
*   **Hardware Relevance:** This software-based work is informed by professional experience with **cryogenic systems (4 K), VNA S-parameter analysis, and low-noise amplifier characterization** at ISRO.

---

## 🔗 Connect & Learn More

*   **Email:** [asmitasayaji21@gmail.com](mailto:asmitasayaji21@gmail.com)
*   **Professional CV:** [Download PDF](./Asmeeta_Quantum_CV.pdf)


---
*This portfolio was created as part of my application and research for PhD positions in experimental quantum computing.*
