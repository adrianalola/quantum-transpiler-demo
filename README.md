🧬 Quantum Transpiler Optimization Demo

This project demonstrates how a quantum circuit is transformed, optimized, and mapped to a backend using Qiskit’s transpiler pipeline.

🔍 Features

Builds a 3-qubit circuit (Grover-style)

Runs transpilation with optimization levels 0–3

Compares:

Circuit depth

Gate counts

Structural changes in the circuit

Uses a standard simulator backend

Clean minimal example of quantum compiler behavior

🧠 Why this matters

Quantum software architecture relies on efficient compilation.
This demo shows how the compiler adapts a logical circuit to hardware constraints, which is essential for:

hardware–software co-design

reducing errors

respecting device connectivity

minimizing depth for limited coherence times

🧪 Requirements
  ```bash
pip install qiskit qiskit_ibm_runtime
  ````

▶️ How to run

Run the notebook in Jupyter, IBM Quantum Lab, or qBraid.
