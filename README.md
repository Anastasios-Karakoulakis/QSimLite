# QSimLite  
A Lightweight Quantum Statevector Simulator in Python

---

## Overview  
QSimLite is a lightweight quantum statevector simulator developed in Python as part of the course **Quantum Computing for Computer Scientists (DD2367)**.  
It provides a simple and educational framework for representing and manipulating quantum states using **linear algebra operations only**.

The simulator models qubits as complex-valued statevectors and supports the application of standard quantum gates (e.g., Hadamard, Pauli-X, and CNOT) through unitary matrix transformations.

---

## Project Goals  
- Implement a statevector-based quantum simulator using only NumPy and basic linear algebra.  
- Develop and test the Quantum Fourier Transform (QFT) and its approximate version (AQFT).  
- Conduct experiments evaluating:  
  - Runtime performance as a function of the number of qubits (n).  
  - Fidelity of AQFT relative to QFT under different truncation levels.

---

## Features  
- Qubit and multi-qubit state representation.  
- Implementation of common quantum gates (Hadamard, Pauli-X, CNOT, etc.).  
- Support for QFT and AQFT experiments.  
- Comparison with Qiskit for correctness verification.

---

## Experiments  
QSimLite includes a series of experiments demonstrating:  
- The scaling of runtime with the number of qubits (n).  
- The trade-off between accuracy and efficiency in approximate QFT (AQFT).  

Detailed results and figures can be found in the accompanying project report (**QSimLite_Report.pdf**).

---

