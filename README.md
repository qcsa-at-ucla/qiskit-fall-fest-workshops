# Qiskit Fall Fest Workshops

Welcome to the UCLA Qiskit Fall Fest workshop materials! This repository contains hands-on Jupyter notebook labs designed to help participants learn quantum computing with IBM Qiskit, from fundamentals to advanced applications.

## Workshop Labs

This repository includes three progressive workshop labs:

### 🟢 Beginner: Qiskit Fundamentals Lab
**File:** `qiskit_fundamentals_lab-2.ipynb`

A comprehensive introduction to Qiskit 2 fundamentals covering 18 core concepts through hands-on exercises. Perfect for those new to quantum computing or Qiskit.

**Topics covered:**
- Pauli operators and single-qubit operations
- Quantum circuits and gates
- Quantum state visualization
- Circuit simulation with Qiskit Aer
- Parameter handling and circuit composition
- Basic quantum algorithms

### 🟡 Intermediate: DiVincenzo Criteria Lab
**File:** `divincenzo_criteria_lab-2 (Intermediate).ipynb`

Explore the fundamental requirements for building a quantum computer through DiVincenzo's five criteria. This lab provides practical demonstrations using Qiskit to understand what makes quantum computing possible.

**Topics covered:**
- Scalable physical systems and qubit characterization
- Qubit initialization and state preparation
- Decoherence times and quantum coherence (T₁, T₂)
- Universal quantum gate sets
- Qubit measurement capabilities
- Running circuits on simulators vs. real IBM Quantum devices

### 🔴 Advanced: Sample-based Quantum Diagonalization (SQD) Lab
**File:** `SQD lab (Advanced) .ipynb`

Dive into cutting-edge quantum algorithms for chemistry applications. Learn how to compute ground state energies of molecules using sampling-based quantum diagonalization methods.

**Topics covered:**
- Sample-based Quantum Diagonalization (SQD)
- Sample-based Krylov Quantum Diagonalization (SKQD)
- Ansatz design and comparison
- Molecular Hamiltonian construction
- Ground state energy calculations for N₂ molecules
- Real quantum hardware execution (~2 min QPU time)

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- IBM Quantum account (for running on real quantum hardware)

### Installation
Each notebook contains installation instructions for the required packages. Generally, you'll need:

```bash
pip install qiskit[visualization] qiskit-ibm-runtime qiskit-aer
```

For the advanced lab, additional packages are required:
```bash
pip install ffsim qiskit-addon-sqd
```

### Usage
1. Clone this repository
2. Open the desired notebook in Jupyter
3. Follow the instructions within each notebook
4. Complete the exercises and ask any questions as you progress

## Event Information

These workshops are part of the **UCLA Qiskit Fall Fest 2025** event organized by the Quantum Computing Student Association (QCSA) at UCLA.

- **Event Website:** [qiskit-fall-fest-ucla](https://qiskit-fall-fest-ucla.vercel.app)
- **Dates:** October 18-19, 2025
- **Learn more about QCSA:** [QCSA Website](https://qcsa-ucla.org)

## Resources

- [IBM Quantum Learning](https://quantum.cloud.ibm.com/learning)
- [Qiskit Documentation](https://docs.quantum.ibm.com/)
- [Qiskit Fall Fest 2025](https://research.ibm.com/events/qiskit-fall-fest-2025)

## License

See [LICENSE](LICENSE) file for details.

## Contact

For questions or support, contact the UCLA Quantum Computing Student Association:
- Email: quantum.ucla@gmail.com
- Instagram: [@uclaqcsa](https://www.instagram.com/uclaqcsa)
- LinkedIn: [QCSA at UCLA](https://www.linkedin.com/company/quantum-computing-student-association-ucla)
