# Lab 4: An Introduction to Quantum Error Correction

Welcome to **Lab 4** of QGSS 2025!  
In this lab, you’ll learn how quantum computers can protect fragile quantum information using **Quantum Error Correction (QEC)**. You will implement **Shor's code**, explore the **stabilizer formalism**, and work with **logical operators** to correct errors on quantum data.  

---

## Lab Overview

In **Lab 4**, you will:  
- Understand **quantum noise** and why error correction is necessary.  
- Build **bit-flip** and **phase-flip codes** step by step.  
- Combine them into the **full 9-qubit Shor code**.  
- Learn how to **measure stabilizers** and apply **logical operators**.  
- (Bonus) Implement a **fault-tolerant CNOT gate** between logical qubits.  

---

## Step-by-Step Workflow

### **0. Setup: Gathering Our Tools**
- Install Qiskit and the grader package (from Lab 0 setup).  
- Verify that you have **Qiskit ≥ 2.0.0** and **Grader ≥ 0.22.9**.  
- Ensure your IBM Cloud account is configured.  
- Import Qiskit, Qiskit Aer, Qiskit Runtime, and visualization tools.  

---

### **1. Introduction to Quantum Error Correction (QEC)**  
- Learn how quantum information is corrupted by **bit-flip**, **phase-flip**, and general noise.  
- Understand how **QEC encodes a logical qubit into multiple physical qubits** to detect and correct errors without collapsing the quantum state.  
- Explore **Shor's code**, a foundational QEC code that corrects any single-qubit error.  

---

### **2. Shor’s Code for Bit-flip Errors**  
**Exercise 1:**  
- Build the **3-qubit bit-flip code**.  
- Encode a logical qubit into `|000⟩` and `|111⟩` states to protect against Pauli-X errors.  

---

### **3. Shor’s Code for Phase-flip Errors**  
**Exercise 2:**  
- Build the **3-qubit phase-flip code**.  
- Use **Hadamard gates** to convert phase errors into bit errors and correct them using redundancy.  

---

### **4. The Full 9-qubit Shor Code**  
**Exercise 3:**  
- Combine bit-flip and phase-flip codes using **concatenation**.  
- Implement the full **Shor code encoding circuit** that protects against any single-qubit error.  

---

### **5. The Stabilizer Formalism**  

#### **5.1 Stabilizer Measurements**  
**Exercise 4:**  
- Learn how to detect errors using **stabilizer measurements**.  
- Build a circuit to measure the stabilizer `ZIZIIIIII` and identify error syndromes.  

#### **5.2 Logical Operators**  
**Exercise 5:**  
- Implement the **logical X operator (X_L = X⊗X⊗…⊗X)** on the encoded qubit.  

**Exercise 6:**  
- Implement the **logical Z operator (Z_L = Z⊗Z⊗Z)** on the encoded qubit.  

---

### **6. (Bonus Challenge) Fault Tolerance**  
- Understand how **fault-tolerant gates** prevent errors from spreading across code blocks.  
- Implement a **fault-tolerant CNOT gate** using **transversal operations** between two Shor-encoded qubits.  

---

## Key Learning Outcomes  
- Built **bit-flip**, **phase-flip**, and **full Shor codes** for quantum error correction.  
- Learned to **measure stabilizers** to detect errors and apply **logical operators**.  
- Understood how to **encode logical qubits** and protect them from single-qubit errors.  
- Explored the concept of **fault tolerance** in quantum computing.  

---

