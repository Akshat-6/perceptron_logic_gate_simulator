# perceptron_logic_gate_simulator
Single-layer perceptron implementation in Python to simulate basic and complex logic gates using a step activation function.


🤖 Single-Layer Perceptron & Logic Gate Simulation
This project demonstrates the implementation of a Single-Layer Perceptron (SLP) using Python to perform binary classification and simulate various logic gates including both basic and complex types.

🧠 Objective
Implement a perceptron from scratch using Python.

Classify binary inputs using a step activation function.

Simulate logic gates (AND, OR, NOT, NAND, NOR, XOR, XNOR) using perceptron-based learning.

Validate results against truth tables.

✅ Tasks Covered
🔸 1. Perceptron for Binary Classification
Step activation function

Weight and bias update using perceptron learning rule

Trained on simple binary dataset (e.g., linearly separable)

🔸 2. Basic Logic Gates
Designed perceptrons for:

AND Gate

OR Gate

NOT Gate

Manually set weights and biases or trained using data

🔸 3. Complex Logic Gates
Extended logic to implement:

NAND and NOR Gates

XOR and XNOR Gates (non-linearly separable — handled via logic composition or custom workaround)

📊 Logic Gate Simulation
Gate	Inputs	Output
AND	(0,0)	0
(1,1)	1
OR	(0,1)	1
NOT	(0)	1
NAND	(1,1)	0
NOR	(0,0)	1
XOR	(1,0)	1
XNOR	(1,1)	1

Note: XOR/XNOR require multiple perceptrons or logic composition due to non-linearity.

🛠️ Technologies Used
Python

NumPy

Matplotlib (for visualizations)

🧪 Results & Observations
Perceptron successfully classifies basic gates (linearly separable)

Complex gates require:

Multiple layers or neurons

Logic gate chaining for XOR/XNOR

