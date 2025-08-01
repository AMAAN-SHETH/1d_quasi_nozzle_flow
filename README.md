# Quasi 1D Nozzle Flow Solver

This project implements 1D compressible flow through a variable-area nozzle using the Quasi-1D Euler equations. The simulations are based on the methods and test cases presented in *"Computational Fluid Dynamics"* by John D. Anderson.

##  Cases Implemented
1. **Non-Conservation Form** – Using MacCormack scheme  
2. **Conservation Form** – Solves conservation equations explicitly  
3. **Subsonic Nozzle** – Nozzle flow with area variation and back pressure  
4. **Shock Capturing** – Captures shocks using the conservation form equations

##🛠️ Methods Used
- Finite difference method
- MacCormack predictor–corrector scheme
- Explicit time stepping
- Area-variation functions for converging-diverging nozzles

## 📚 Reference
All cases are adapted from:  
*J. D. Anderson – Computational Fluid Dynamics: The Basics with Applications*

