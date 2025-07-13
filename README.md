# 🧠 TGNAS Neuron – A C++ Neural Network from Scratch

This project is a hand-crafted implementation of a **single-layer linear regression model** (a.k.a. a basic neuron) using **pure C++** — no external libraries, no frameworks, just raw math and logic.

Inspired by a hands-on session on "Build Your First Neural Network," this model demonstrates how the **core mechanics** of machine learning (like gradient descent and ReLU activation) work under the hood.

> 🔢 The model’s logic is based on a quirky mathematical signature derived from the name **TGNAS**:
>
> `T = 20, G = 7, N = 14, A = 1, S = 19`  
> Resulting in a formula: `y = 20x - 7x + 14x - 1x + 19x`

---

## 🚀 What It Does

- Implements a **simple linear regression** model
- Trains using **gradient descent**
- Uses a **ReLU activation function** manually coded in C++
- Accepts live user input and makes real-time predictions
- Exits gracefully when you enter the keyword `TGNAS`

---

## 📚 Key Concepts Covered

- Linear regression
- Gradient descent
- Loss calculation
- ReLU (Rectified Linear Unit)
- Overfitting avoidance (with learning rate tuning)
- Manual weight & bias updates

---

## 🔧 How to Run

### Prerequisites
- C++ compiler (e.g., `g++`)
- Terminal or command prompt

### Compile & Run
```bash
g++ -o tgnasNeuron tgnasAlgo.cpp
./tgnasNeuron

Enter the value to predict : 10
Prediction for 10 is : 450.12

Enter the value to predict : TGNAS
Exiting Cya!!
