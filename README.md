# Quantum Random Number Generator (QRNG) using Qiskit

## Project Summary
This small project generates true random bits using quantum superposition and measurement. It uses Qiskit to create a single-qubit circuit, apply a Hadamard gate, and measure the result. Repeating this process yields an n-bit random binary string.

## Installation
```bash
python -m venv venv
source venv/bin/activate     # Linux / macOS
venv\Scripts\activate        # Windows
```
## What is Qiskit?

**Qiskit (Quantum Information Science Kit)** is an open-source quantum computing framework developed by IBM Quantum.
It allows developers, researchers, and students to build, simulate, and run quantum circuits on both classical simulators and real quantum computers.

Qiskit provides tools for:

 1. **Quantum Circuit Construction**

    Create quantum algorithms using logical gates (Hadamard, CNOT, Pauli gates, etc.) and measurement operations.

2. **Quantum Simulation**

Run quantum circuits locally using high-performance simulators such as:

`Aer`

`AerSimulator`

`BasicAer`

3. **Execution on Real Quantum Hardware**

If you have an IBM Quantum account, you can run your circuits on real quantum devices with:

```bash
from qiskit_ibm_provider import IBMProvider
```
4. **Quantum Machine Learning & Optimization (Extensions)**

Through modules like:

- Qiskit Machine Learning

- Qiskit Optimization

- Qiskit Nature

5. **Visualization Tools**

Qiskit provides beautiful visualizations such as:

- quantum circuit diagrams

- statevector & Bloch sphere plots

- measurement histograms

- probability distributions

## Why Qiskit Matters

Qiskit is the leading framework for practical quantum computing because:

1. It is Python-based → easy to learn

2. It is open-source

3. It is connected to real quantum hardware

4. It supports research, education, and industry

5. It has active development and documentation

This makes Qiskit ideal for hands-on projects like Quantum Random Number Generators, quantum algorithms, quantum ML, and simulations.
