# Qiskit-Fall-Fest-Hackathon
Contains code implementation of hackathon prompt


This project demonstrates how to create a **random number** using the concept of **uniform superposition** of all possible qubit states in a quantum circuit — a foundational concept in quantum computing. By applying Hadamard gates to each qubit initialized in the |0⟩ state, the circuit ensures that every possible combination of qubits (e.g., |00...0⟩, |00...1⟩, ..., |11...1⟩) has the **same probability** of measurement.

---

## Concept

A single qubit in the |0⟩ state, when passed through a **Hadamard (H) gate**, transforms into a superposition state of 0 and 1.
By applying this gate to multiple qubits, you can get a combination of states which will represent the bit transformation of a decimal value, perfectly simulating a random number since each statevector (qubit combinations) will have the same probability.

Circuit was run on a fake backend with error simulated using qiskit-aer
Error mitigation technique known as Pauli Check Sandwiching was used to mitigate errors in this circuit.




