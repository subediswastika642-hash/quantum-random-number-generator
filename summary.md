# 1. The Problem and the Quantum Solution
## The Problem
The problem of classical computer is that it cannot handle problems that needs explonential complexity. Classical randomness can be predictable which is the problem.
## The Quantum Solution
The quantum randomness is unpredictable, ubiased and purely natural. It is used to put qubits into superposition, measure them and get a truly random number. The project uses a real Quantum Random Number Generator using Qiskit.
# Code Explanation
## Defination of Quantum System
qc= QuantumCircuit(qubits_count,qubits_count)
I create a system with N quantum wires i.e. qubits and N classical wires. I used qubit_count equal to 4 and Total possible outcomes from Range 0 to 15.
## Prepare Superposition 
I applied a Hadamard (H) gate to each qubit. Every posible 4 bit state is equally likely to a perfect randomness.
# Presentation Layer Explanation 
As I wanted a user friendly and visually attractive output, I added a clean presentation layer to make experience feel like using a real QRNG tool.
# Conclusion
My project illustrates Quantum Random Number Generator by using Qiskit and AerSimulator. My QRNG uses 4-qubit quantum circuit. Each qubit is placed in superposition using H gate, which allows it to exist in both 0 and 1 at the same time. When qubits are measured then the quantum state collapses which produce a random 4 bit binary string. Then, this string is converted into an integer between 0 to 15.
This project contains a clean presentation layer. It explains the system definition, total spate space, output range, and final generated integer. 
Generally, this project shows how quantum computing can solve a practical problems by using minimum quantum circuit.

