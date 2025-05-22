# TaylorRootFinder-HighOrderNewton
Fourth-order Newton root-finding method derived via Taylor expansion and implemented symbolically in Maple.

## Project Overview
The goal of this work is to improve the classical Newton-Raphson method by using a Taylor series expansion to derive a fourth-order iterative formula. This higher-order method can achieve faster convergence under appropriate smoothness assumptions.
The method was derived step by step, starting from the Taylor expansion of a nonlinear function \( f(x) \), followed by algebraic simplification to express the root update in terms of \( f(x), f'(x), f''(x), f'''(x) \). The final expression was verified and then implemented using symbolic computation in Maple.

---

## Contents
| File | Description |
|------|-------------|
| `HighOrderNewton.mw` | Maple worksheet containing derivation, implementation, and testing |
| `README.md` | Project overview |
| `Results.txt` | Sample output for selected functions and initial guesses |

---

## Key Features
- Full symbolic derivation using Taylor expansion
- Maple implementation using modules and procedure definitions
- Tested on various functions to validate convergence and accuracy
- Code modularized for reuse and extension

---

## How to Run
1. Open the `.mw` file in Maple (tested on Maple 2023).
2. Step through the derivation or run all at once.
3. Adjust the function or initial value in the test section to explore convergence behavior.

---

## Author
Claire Du  
MSc Financial Mathematics  
University of Liverpool  


