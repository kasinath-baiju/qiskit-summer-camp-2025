# Qiskit Global Summer School 2025 — Labs Repository

This repository contains my solutions and notes for **Lab 0 through Lab 4** of the Qiskit Global Summer School 2025. Each lab builds on the last, exploring core quantum computing concepts and practical implementations using Qiskit.

---

##  Repository Structure

```

/
├── Lab0/
│   └── README.md
├── Lab1/
│   └── README.md
├── Lab2/
│   └── README.md
├── Lab3/
│   └── README.md
├── Lab4/
│   └── README.md
└── README.md   ← (this master overview)

````

---

##  Labs Overview

### **Lab 0: Hello Quantum World!**
- Setup Qiskit and the grading toolkit.
- Configure your IBM Quantum account for access to simulators and real hardware.
- Create a 3-qubit GHZ state using Qiskit Patterns:
  1. Map: Build the GHZ circuit.
  2. Optimize: Transpile for hardware constraints.
  3. Execute: Run with Sampler and Estimator.
  4. Post-process: Analyze results (~50% in `000` and `111`).
- Bonus: Run on real hardware and observe noise.

---

### **Lab 1: Recreating Famous Experiments at Home!**
- Explore quantum phenomena via simulations:
  1. **Double-Slit Experiment** – superposition, interference, phase shifts, and visibility of fringes.
  2. **Schrödinger’s Cat Thought Experiment** – demonstrate measurement collapse.
  3. **Double-Slit with Path Detection** – observe disappearance of interference upon measurement.
  4. **CHSH Game (Entanglement)** – create a Bell pair and demonstrate quantum correlations exceeding classical limits (~85% win).
  5. **Quantum Teleportation Protocol** – transfer an unknown qubit state using entanglement and classical communication.
- Bonus: Execute the teleportation circuit on real quantum hardware.

---

### **Lab 2: QAOA and Error Mitigation**
- Dive into the **Quantum Approximate Optimization Algorithm (QAOA)** applied to the **Max-Cut problem**:
  1. Define the Max-Cut cost Hamiltonian.
  2. Create the mixer Hamiltonian.
  3. Build the QAOA ansatz circuit.
  4. Implement a hybrid optimization loop using Qiskit’s Estimator.
  5. Post-process to identify optimal solutions.
- Learn **Error Mitigation Techniques**:
  - **Zero-Noise Extrapolation (ZNE)** – mitigate noise by extrapolating to zero noise.
  - Additional techniques covered conceptually: Probabilistic Error Cancellation and Dynamical Decoupling.

---

### **Lab 3: An Introduction to Quantum Machine Learning**
- Explore **Quantum Kernel Methods**:
  1. Build a **quantum feature map** (ZFeatureMap).
  2. Construct a **quantum kernel** using fidelity measurements.
  3. Train and evaluate a **quantum support vector classifier (PegasosQSVC)**.
- Develop **Quantum Neural Networks (QNNs)**:
  - Combine a feature map and parametric circuit (TwoLocal ansatz).
  - Build and train a **NeuralNetworkClassifier** using Qiskit’s EstimatorQNN.
- Bonus: Apply QML techniques to classify the **Wine dataset** from scikit-learn.

---

### **Lab 4: An Introduction to Quantum Error Correction**
- Learn how to protect quantum information using **Quantum Error Correction (QEC)**:
  1. Implement the **3-qubit bit-flip code** to correct X errors.
  2. Implement the **3-qubit phase-flip code** to correct Z errors.
  3. Combine them into the **9-qubit Shor code** to correct arbitrary single-qubit errors.
  4. Use the **Stabilizer Formalism** to detect errors.
     - Build circuits to measure stabilizer operators.
  5. Apply **Logical Operators** (logical X and Z) on encoded qubits.
  6. Bonus: Implement a **fault-tolerant logical CNOT** between Shor-encoded qubits using transversal logic.

---

##  Additional Details
- Each lab folder contains a dedicated README with a descriptive summary of its exercises.
- All notebooks are designed to be auto-graded using the `qc-grader` package.
- You do **not** need to include your certificate in this repository—keep it private or share it via the official platform if needed.

---

##  How to Use This Repo
1. Clone the repository:
    ```bash
   git clone https://github.com/kasinath-baiju/qgss-labs.git
    cd qiskit-summer-camp-2025
   ```
    
2. Install dependencies:
    ```bash
    pip install "qc-grader[qiskit,jupyter] @ git+https://github.com/qiskit-community/Quantum-Challenge-Grader.git"
    ```
3. Open Jupyter notebooks in each lab folder and follow the steps.

---

##  License
This repository is created for educational purposes as part of the **Qiskit Global Summer School 2025**.

---
