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

## 📦 Installation & Setup

Follow these steps to get the calculator running on your local machine:

1.  **Check for `bc`:**
    Ensure you have the `bc` (Basic Calculator) utility installed. It is required for the script's mathematical operations.
    ```bash
    # On Debian/Ubuntu:
    sudo apt-get install bc
    
    # On macOS:
    brew install bc
    ```

2.  **Create the script:**
    Save the code into a file named `calc.sh`.

3.  **Make the script executable:**
    Open your terminal and run the following command:
    ```bash
    chmod +x calc.sh
    ```

---

## Usage

To start the calculator, execute the script from your terminal:
```bash
./calc.sh

## Example Output
```bash
1. Calculate area of a circle
2. Calculate area of a rectangle
3. Solve quadratic equation (ax² + bx + c = 0)
4. Exit
Enter your choice (1-4): 1
Enter the radius of the circle: 5
The area of the circle with radius 5 is: 78.53 square units
