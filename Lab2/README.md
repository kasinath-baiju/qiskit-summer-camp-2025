# Lab 2: Quantum Error Mitigation and Real Hardware  

Welcome to **Lab 2** of QGSS 2025!  
This lab introduces **quantum noise**, **error sources**, and techniques for **error mitigation** using Qiskit.  

---

## Lab Overview  

In **Lab 2**, you will:  
- Understand why quantum devices are noisy.  
- Learn how to use Qiskit tools to **characterize noise**.  
- Implement **error mitigation techniques** to improve results.  
- Run circuits on **real quantum hardware** and compare with simulation.  

---

## Step-by-Step Workflow  

### **Chapter 1: Introduction to Quantum Noise**  

**Exercise 1: Simulate a Noisy Quantum Circuit**  
- Add artificial noise models (e.g., depolarizing or readout error).  
- Compare noisy and ideal results.  

**Exercise 2: Error Characterization**  
- Run calibration circuits to estimate **readout error probabilities**.  
- Visualize how noise affects measurement distributions.  

---

### **Chapter 2: Error Mitigation Techniques**  

**Exercise 3: Readout Error Mitigation**  
- Use Qiskit’s built-in routines to correct measurement bias.  
- Apply mitigation filters to your results.  

**Exercise 4: Zero-Noise Extrapolation (ZNE)**  
- Execute circuits at scaled noise levels.  
- Extrapolate results back to the **zero-noise limit**.  

**Exercise 5: Clifford Data Regression (Optional)**  
- Explore an advanced method to reduce errors on real devices.  

---

### **Chapter 3: Running on Real Hardware**  

**Exercise 6: Execute Mitigated Circuits on IBM Quantum Device**  
- Use Qiskit Runtime to submit jobs to real hardware.  
- Compare:  
  - **Ideal simulation**  
  - **Noisy simulation**  
  - **Real hardware with mitigation applied**  

---

## Key Learning Outcomes  
- Gained intuition about **quantum noise** and its effects.  
- Learned to **measure and mitigate errors** in quantum circuits.  
- Practiced running circuits on **IBM Quantum backends**.  
- Compared simulation results to real-device behavior using mitigation.  

---

