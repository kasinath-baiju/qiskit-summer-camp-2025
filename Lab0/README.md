# Lab 0: Hello Quantum World!  

Welcome to the **Qiskit Global Summer School 2025**!  
This introductory lab is designed to help you set up your environment, connect to IBM Quantum hardware, and get familiar with the Qiskit Patterns workflow by creating a three-qubit GHZ state.  

---

## Lab Overview  

In **Lab 0**, you will:  
- Install Qiskit and the grader package.  
- Configure your IBM Quantum account.  
- Learn to use **Qiskit Patterns** (Map → Optimize → Execute → Post-process).  
- Create and verify a **three-qubit GHZ state**.  
- Optionally, run your circuit on **real quantum hardware**.  

---

## Step-by-Step Workflow  

### **0. Setup and Installation**  
- Verify Python 3.10 or higher.  
- Install `qc-grader` (which includes Qiskit 2.x).  
- Confirm correct installation of Qiskit and Grader packages.  
- Set up your IBM Quantum account using your API key and CRN.  

---

### **1. Map: Design the GHZ Circuit**  
**Exercise 1:**  
- Apply a **Hadamard gate** on qubit 0.  
- Apply a **CNOT gate** between qubits 0 → 1.  
- Apply a **CNOT gate** between qubits 1 → 2.  
- This creates the target GHZ state:  
  \|GHZ⟩ = ( \|000⟩ + \|111⟩ ) / √2  

---

### **2. Optimize: Transpile for Hardware Constraints**  
**Exercise 2:**  
- Assume hardware only allows CNOTs between qubits (0,1) and (0,2).  
- Use Qiskit’s **PassManager** to transpile the GHZ circuit for this restricted coupling map.  

---

### **3. Execute: Run the Circuit**  
- Use Qiskit Runtime **Sampler** to get measurement counts.  
- Use **Estimator** to compute expectation values of relevant observables.  

---

### **4. Post-process: Analyze Results**  
- Verify that the Sampler outputs ~50% probability for both `000` and `111`.  
- Check Estimator expectation values to confirm correct GHZ behavior.  

---

## Bonus Challenge: Run on Real Quantum Hardware  
- Use `QiskitRuntimeService` to select the least busy backend.  
- Run the GHZ experiment on an actual quantum device to observe **noise effects**.  

---

## Key Learning Outcomes  
- Successfully set up your Qiskit environment and IBM Quantum account.  
- Built and analyzed a three-qubit GHZ state using Qiskit Patterns.  
- Learned to optimize circuits for constrained hardware.  
- Compared simulation results with noisy real-device outputs.  

---
