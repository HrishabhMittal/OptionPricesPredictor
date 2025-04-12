# Quantum European Option Pricing with PennyLane

This project demonstrates how quantum computing techniques can be applied to predict the price of **European call and put options** using the **Black-Scholes model** in combination with the **PennyLane** quantum machine learning framework.

## What is this project?

This project implements a hybrid classical-quantum workflow to price European options. While the **Black-Scholes model** provides an analytical method for option pricing, this project uses **PennyLane** to approximate the pricing function using quantum circuits, serving as a demonstration of quantum-enhanced financial modeling.

## Key Concepts

- **European Options**: Options that can only be exercised at expiration.
- **Black-Scholes Model**: A mathematical model used to determine the theoretical price of options.
- **Quantum Machine Learning (QML)**: Combining quantum computing with machine learning to potentially gain computational advantages.
- **PennyLane**: A quantum machine learning library that integrates quantum computing with PyTorch, TensorFlow, and NumPy.

## Features

- Calculates the exact option price using the Black-Scholes formula.
- Approximates option prices using a parameterized quantum circuit.
- Uses gradient-based optimization to train the quantum model.
