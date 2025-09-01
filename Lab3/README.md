# Lab 3: An Introduction to Quantum Machine Learning  

Welcome to **Lab 3** of QGSS 2025!  
In this lab, you’ll explore **Quantum Machine Learning (QML)** — an exciting field at the intersection of quantum computing and machine learning. You will build **quantum kernel methods**, **quantum support vector classifiers**, and **quantum neural networks (QNNs)** using Qiskit Machine Learning.  

---

## Lab Overview  

In **Lab 3**, you will:  
- Learn the fundamentals of **Quantum Kernel Methods** and **Quantum Neural Networks**.  
- Implement a **quantum feature map** and build a **quantum kernel**.  
- Train and evaluate a **quantum support vector classifier (PegasosQSVC)**.  
- Construct a **variational quantum neural network (QNN)** and train it on sample data.  
- (Bonus) Apply QML techniques to a **real-world dataset (Wine dataset)**.  

---

## Step-by-Step Workflow  

### **0. Setup: Gathering Our Tools**  
- Install Qiskit and the grader package (from Lab 0 setup).  
- Verify that you have **Qiskit ≥ 2.0.0** and **Grader ≥ 0.22.9**.  
- Import the required Qiskit and scikit-learn libraries.  

---

### **1. Introduction to Quantum Machine Learning (QML)**  
- Understand how **quantum circuits** can encode data and enable new machine learning algorithms.  
- Explore how **quantum feature spaces** may reveal patterns difficult to detect classically.  

---

### **2. Quantum Kernel Methods**  

#### **2.1 Feature Maps**  
**Exercise 1:**  
- Build a **ZFeatureMap** for 2 qubits with 2 repetitions.  
- Understand how classical data is embedded into quantum states.  

#### **2.2 Quantum Kernels**  
**Exercise 2:**  
- Use the **FidelityQuantumKernel** to compute state overlaps.  
- Learn how quantum kernels measure similarity between data points.  

#### **2.3 Quantum Support Vector Classifier**  
**Exercise 3:**  
- Train a **PegasosQSVC** on an artificially generated dataset (`adhoc_dataset`).  
- Evaluate classifier accuracy on test data.  

---

### **3. Quantum Neural Networks (QNNs)**  

#### **3.1 Building a QNN**  
**Exercise 4:**  
- Construct a QNN by combining a **ZFeatureMap** (input encoding) with a **TwoLocal ansatz** (parameterized circuit).  
- Understand how variational circuits form the "neural network" component.  

#### **3.2 Training a QNN**  
**Exercise 5:**  
- Define an **EstimatorQNN** with an observable for classification.  
- Train a **NeuralNetworkClassifier** using Qiskit Machine Learning’s optimizers.  
- Evaluate performance on the test dataset.  

---

### **4. (Bonus Challenge) Real-World QML on the Wine Dataset**  
- Load and preprocess the **Wine dataset** (feature scaling, dimensionality reduction with PCA).  
- Train a **PegasosQSVC** using your quantum kernel.  
- Evaluate how QML techniques handle real-world data classification.  

---

## Key Learning Outcomes  
- Learned how **quantum feature maps** and **quantum kernels** enable quantum-enhanced classification.  
- Trained and evaluated a **quantum SVM (PegasosQSVC)**.  
- Built and trained a **Quantum Neural Network (QNN)** using variational quantum circuits.  
- Gained practical experience applying QML to both synthetic and real-world datasets.  

---

