# Interactive Linux Bash Calculator

A robust command-line interface (CLI) tool for geometric calculations and algebraic equation solving. This script leverages the `bc` (Basic Calculator) utility to handle floating-point arithmetic with high precision.

---

## Features

* **Circle Area:** Calculates the area of a circle using the formula $A = \pi r^2$.
* **Rectangle Area:** Computes the area of a rectangle ($A = L \times W$).
* **Quadratic Solver:** Solves for real roots using the quadratic formula:
    $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
* **Floating Point Precision:** Uses `scale` in `bc` to ensure accurate decimal results.
* **Input Validation:** Features an interactive menu loop with error handling for invalid menu choices.

---

## Prerequisites

This script requires the `bc` utility. Most Unix-like systems (Linux, macOS) have this pre-installed. 

To verify installation, run:
```bash
which bc
