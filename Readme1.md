# Quantum Computing Research Portfolio

**Asmeeta Prakash Sayaji** | [Email](mailto:asmitasayaji21@gmail.com) | [CV](Asmeeta_Quantum_CV.pdf) | [Full Research Portfolio (PDF)](Research_Portfolio_Asmeeta_Prakash_Sayaji.pdf)

Ahmedabad, India

---

## Overview

This repository contains the code and simulations for my self-directed research in quantum computing. This work bridges my professional background in **cryogenic microwave engineering at ISRO** with the software and theoretical foundations of superconducting quantum computation. It demonstrates a practical understanding of quantum algorithms, noise processes, and pulse-level control, directly relevant to experimental device characterization and error mitigation.

> **📄 For a detailed analysis, discussion, and critical insights, please see the formal [Research Portfolio PDF](Research_Portfolio_Asmeeta_Prakash_Sayaji.pdf).**

## 📁 Research Project Structure

The research is structured to reflect a progression from fundamental principles to advanced topics:

### 1. Foundations of Quantum Circuits & Entanglement
*   **`1a_bell_states.ipynb`**: Generation and measurement sampling of Bell states to study entanglement statistics.
*   **`1b_statevector_simulation.ipynb`**: Noise-free quantum circuit simulation for algorithm benchmarking.

### 2. Understanding Quantum Noise and Decoherence
*   **`2a_depolarizing_noise.ipynb`**: Modeling Bell state decoherence under generic depolarizing quantum noise.
*   **`2b_superconducting_t1_t2_noise.ipynb`**: Simulation of realistic noise channels (T₁, T₂, depolarizing) for transmon-like qubits.

### 3. Quantum Algorithm Implementation & Advantage
*   **`3a_grover_2_qubit.ipynb`**: Implementation and analysis of a 2-qubit Grover search algorithm.
*   **`3b_deutsch_jozsa_n3.ipynb`**: Demonstration of deterministic quantum advantage using the n=3 Deutsch-Jozsa algorithm.

### 4. Advanced Research: Open Systems & Pulse-Level Control
*   **`4a_lindblad_qubit_dynamics.ipynb`**: Modeling non-unitary dynamics of a driven transmon qubit using the Lindblad master equation in QuTiP.
*   **`4b_drag_pulse_design.ipynb`**: Design and simulation of DRAG pulses for leakage suppression in |1⟩→|2⟩ transitions.

## 🛠️ Technical Skills Demonstrated

*   **Quantum Frameworks**: Qiskit (Terra, Aer, Pulse), OpenQASM, QuTiP
*   **Programming**: Python (NumPy, SciPy, Matplotlib)
*   **Quantum Concepts**:
    *   Quantum Noise & Decoherence (T₁, T₂)
    *   Lindblad Master Equation for Open Quantum Systems
    *   Quantum Error Mitigation (ZNE)
    *   Pulse-Level Control (DRAG)
    *   Transmon Qubit Properties
    *   Quantum Algorithms (Grover, Deutsch-Jozsa)
*   **Hardware Relevance**: Informed by professional experience with cryogenic systems (4 K), VNA S-parameter analysis, and low-noise amplifier characterization at ISRO.

## ⚙️ Setup and Installation

To reproduce the results in these notebooks:

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/Quantum-Computing-Research.git
    cd Quantum-Computing-Research
    ```

2.  (Recommended) Create a virtual environment and install the exact package versions:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```

## 🔗 Connect

*   **Email**: asmitasayaji21@gmail.com
*   **Professional CV**: [Download PDF]([CV](Asmeeta_Quantum_CV.pdf)

---

*This portfolio was created as part of my application and research for PhD positions in experimental quantum computing.*
