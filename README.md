# QAOA for Max-Cut using Qiskit

This tutorial demonstrates how to implement the **Quantum Approximate Optimization Algorithm (QAOA)** using **Qiskit** to solve the **Max-Cut** problem, a classical NP-hard combinatorial optimization challenge. The implementation includes graph modeling, quantum circuit construction, transpilation for real quantum hardware, and execution using Qiskit Runtime Primitives.

---

## 🧠 About QAOA

**QAOA** is a hybrid quantum-classical algorithm designed to tackle combinatorial optimization problems. It leverages a parameterized quantum circuit (Ansatz) and classical optimization techniques to find approximate solutions. QAOA is particularly useful for problems that can be mapped to a **Quadratic Unconstrained Binary Optimization (QUBO)** model.

---

## 📌 Problem: Max-Cut

Given a graph \( G = (V, E) \), the goal of the Max-Cut problem is to partition the set of vertices \( V \) into two disjoint subsets such that the number of edges connecting the subsets is maximized.

---

## 🧮 Prerequisites

- Python 3.8+
- Qiskit (`qiskit`, `qiskit-ibm-runtime`)
- Rustworkx (for graph generation)
- Matplotlib (for drawing graphs)
- IBM Quantum account (for hardware access)

---

## ⚙️ Installation

```bash
pip install qiskit qiskit-ibm-runtime rustworkx matplotlib
