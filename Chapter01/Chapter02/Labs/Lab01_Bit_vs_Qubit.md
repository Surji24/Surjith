# Lab 01 - Bit vs Qubit

## Objective

Understand the difference between a Classical Bit and a Quantum Qubit.

---

# Real World Example 1 - Light Switch

## Classical Computer

A normal switch can be:

OFF = 0

ON = 1

Only one state exists at a time.

Example:

- Router Interface Down = 0
- Router Interface Up = 1

---

# Real World Example 2 - Firewall Rule

Classical Firewall:

Rule Enabled = 1

Rule Disabled = 0

Only one condition can exist.

---

# Quantum Example

Imagine a spinning coin.

Before it lands:

Head ?
Tail ?

Both possibilities exist.

This is similar to a Qubit before measurement.

---

# Bit

Values:

0
1

Example:

Server Status

0 = Down
1 = Up

---

# Qubit

A Qubit can be represented as:

|0⟩

|1⟩

or a quantum combination of both.

---

# Cyber Security Example

Classical Password Attack

Password1
Password2
Password3

One after another.

---

Quantum Concept

Quantum algorithms can exploit quantum effects to search some problems more efficiently than classical methods.

---

# Qiskit Lab

Create file:

bit_vs_qubit.py

Code:

from qiskit import QuantumCircuit

qc = QuantumCircuit(1)

print(qc)

Output:

q:

Meaning:

One Qubit Created

---

# Interview Questions

Q1. What is a Bit?

Answer:

A Bit is the smallest unit of information in classical computing and stores either 0 or 1.

---

Q2. What is a Qubit?

Answer:

A Qubit is the basic unit of information in quantum computing.

---

Q3. Difference between Bit and Qubit?

Answer:

Bit stores 0 or 1.

Qubit follows quantum mechanics and can exist in quantum states before measurement.

---

# Notes

Networking Example:

Switch Port

UP = 1

DOWN = 0

Classical State

Quantum State

Measured as 0 or 1 after observation.

---

# Lab Status

Completed: □
