# Hadamard Gate: Simulator vs Real Quantum Hardware

## 📌 Objective
To demonstrate how a Hadamard gate creates superposition and compare results between a simulator and a real quantum computer.

---

## ⚛️ Concept

A Hadamard gate transforms a qubit from state |0⟩ into a superposition:

|0⟩ → (|0⟩ + |1⟩) / √2

This means equal probability of measuring 0 and 1.

---

## 🧪 Experiment

### 1. Simulator (Statevector)
Result:
{'0': 0.5, '1': 0.5}

---

### 2. Real Quantum Hardware (Rigetti Ankaa-3)
Shots: 100  
Result:
{'0': 52, '1': 48}

---

## 📊 Observation

- Simulator gives perfect 50/50 distribution  
- Real quantum hardware shows slight deviation  

---

## 🔍 Reason

Real quantum computers are affected by:

- Noise  
- Decoherence  
- Gate imperfections  

---

## 🚀 Key Learning

Quantum results are probabilistic and real hardware is not perfect.

---

## 📎 Files

- simulator.ipynb  
- real_qpu_result.json  

---

## ✨ Author

Saikrishna Thopula
