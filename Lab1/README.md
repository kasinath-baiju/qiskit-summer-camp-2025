# Lab 1: Recreating Famous Experiments at Home!  

Welcome to **Lab 1** of QGSS 2025!  
In this lab, you'll explore **superposition, interference, measurement, and entanglement** through quantum experiments implemented with Qiskit.  

---

## Lab Overview  

In **Lab 1**, you will:  
- Recreate **famous quantum experiments** such as the **double-slit** and **Schrödinger’s cat**.  
- Learn how measurement affects quantum systems.  
- Explore **entanglement** and play the **CHSH game**.  
- Implement **quantum teleportation**.  
- (Bonus) Run quantum teleportation on **real IBM hardware**.  

---

## Step-by-Step Workflow  

### **Chapter 1: Superposition, Interference, and Measurement**  

**Exercise 1: Build the Double-Slit Experiment Circuit**  
- 1-1: Create superposition with a Hadamard gate (a "quantum slit").  
- 1-2: Add another Hadamard to simulate interference at the screen.  
- 1-3: Introduce a phase shift to model path differences.  
- 1-4: Parameterize phase to visualize the interference fringe pattern.  

**Exercise 2: Schrödinger’s Cat Thought Experiment**  
- Prepare a qubit in superposition using an RX gate.  
- Perform measurement to demonstrate state collapse.  

**Exercise 3: Double-Slit with Path Detector**  
- Insert a measurement after the first Hadamard to detect the particle’s path.  
- Observe how measurement destroys interference fringes.  

---

### **Chapter 2: Entanglement**  

**Exercise 4: The CHSH Game**  
- Create a Bell state (maximally entangled pair).  
- Apply different measurement bases depending on inputs.  

**Exercise 5: Analyze CHSH Game Results**  
- Verify win probability exceeds **classical limit of 75%** (expect ~85%).  

---

### **Quantum Teleportation**  

**Exercise 6: Implement Teleportation Protocol**  
- Prepare Alice’s qubit in superposition.  
- Share a Bell pair between Alice and Bob.  
- Perform Alice’s Bell-state measurement.  
- Apply Bob’s conditional corrections to reconstruct the original state.  

---

## Bonus Challenge: Run Teleportation on Real Hardware  
- Use **dynamic circuits** on an IBM Quantum backend.  
- Observe noise and gate errors in physical qubits.  

---

## Key Learning Outcomes  
- Understood quantum **superposition** and **interference** via the double-slit experiment.  
- Observed how **measurement collapses quantum states**.  
- Implemented **entanglement** and verified non-classical correlations.  
- Built and simulated a **quantum teleportation circuit**.  
- (Optional) Gained experience executing circuits on **real quantum devices**.  

---
