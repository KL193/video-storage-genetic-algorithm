# Genetic Algorithm for Video Storing Problem

This is a group assignment for the **Evolutionary Computing** course. We implement a solution to the **Video Storing Problem** using a **Genetic Algorithm (GA)**, as introduced in Lecture 04. The solution is developed and tested using **Google Colab** for ease of collaboration and experimentation.

---

## 🎯 Objectives

- Solve the Video Storing Problem using a Genetic Algorithm.
- Experiment with various configurations:
  - Population size variations
  - Different crossover and mutation methods
  - Hyperparameter tuning (e.g., mutation rate, crossover rate)
- Evaluate and compare performance using appropriate metrics.

---

## 📚 Problem Description

The Video Storing Problem involves distributing a set of video files across limited storage servers while minimizing storage usage and access costs, and ensuring constraints are satisfied.

We use a Genetic Algorithm approach which mimics natural selection via:
- **Initialization**
- **Fitness Evaluation**
- **Selection**
- **Crossover**
- **Mutation**
- **Termination**

---

## 🛠️ Technologies & Tools

- **Language**: Python 3 (via Google Colab)
- **Platform**: Google Colab
- **Libraries Used**:
  - NumPy
  - Matplotlib (for visualization)
  - (Others as needed)

---

## ▶️ Running the Project

You can run the implementation directly in Google Colab:

👉 https://colab.research.google.com/drive/1inJEGZX35XvvHbljOhbTTiyhVsU8zBi7?usp=sharing

**Steps to Use:**
1. Open the notebook.
2. Run cells sequentially.
3. Modify experiment parameters (population size, mutation rate, etc.).
4. Visualize and analyze results in the output cells.


## 🧪 Experiments

We conducted multiple experiments by changing:
- **Population sizes**: 50, 100, 200
- **Crossover methods**: One-point, Two-point, Uniform
- **Mutation types**: Bit-flip, Swap
- **Hyperparameters**:
  - Crossover Rate:  0.25 to 0.7
  - Mutation Rate: 0.1 to 0.25

Performance data and graphs are generated inside the notebook itself.



