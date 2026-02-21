## Micrograd From Scratch 🧠

A tiny automatic differentiation engine and neural network library built entirely in pure Python to understand how backpropagation actually works under the hood.

Instead of using PyTorch/TensorFlow, this project recreates the core ideas manually — computational graphs, gradients, and training a neural network.

---

## What it includes
- Scalar `Value` class storing data + gradient
- Dynamic computational graph during forward pass
- Reverse‑mode autodiff (backpropagation)
- Basic operations with gradient tracking
- Neuron → Layer → MLP implementation
- Training using gradient descent

---

## Why I built this
To move from *using* deep learning to actually understanding it:
- Chain rule in practice
- How gradients flow through networks
- What optimizers really update

---

## Outcome
After this project, I
 - Understood how Nerual nets work
 - Built inuition for backpropagation
 - Can now read and understand DL papers and implement with more confidence

