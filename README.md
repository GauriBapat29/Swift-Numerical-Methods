# 🔢 Root-Finding Algorithms

This repository contains implementations of numerical methods for solving **non-linear equations** of the form:

\[
f(x) = 0
\]

Root-finding algorithms are widely used in mathematics, physics, and engineering when analytical solutions are difficult or impossible.

---

## 📌 Implemented Methods

### 1. Müller’s Method
- Uses **quadratic interpolation** through three points.  
- Can approximate **real and complex roots**.  
- Often converges faster than the Secant method.  

### 2. Newton-Raphson Method
- Based on the **first-order Taylor series expansion**.  
- Requires knowledge of the function’s derivative.  
- Converges quadratically near the root, but may diverge if the initial guess is poor.  

### 3. Secant Method
- Similar to Newton-Raphson but does **not require the derivative**.  
- Uses a finite difference approximation for slope.  
- Converges slower than Newton-Raphson but faster than Bisection.  

### 4. Regula Falsi (False Position) Method
- Bracketing method based on a **linear interpolation** between two points.  
- Always convergent if the initial interval contains a root.  
- May converge slowly if one endpoint remains fixed.  

---

## ⚙️ Features
- Simple, modular implementations.  
- Easy to extend for custom functions.  
- Works with polynomials and user-defined equations.  

---

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/root-finding-algorithms.git
   cd root-finding-algorithms
