# Regularity and Chaos in Dynamical Systems

---

## Overview
This project delves into the study of regular and chaotic evolutions in dynamical systems using mathematical models and numerical simulations. It explores the behavior of various systems, including periodic and quasi-periodic evolutions, Henón's Map, and the Lotka-Volterra model. Through detailed analysis and visualization, the project aims to understand the underlying dynamics and characteristics of these systems.

## Dependencies
- Python 3.x
- [NumPy](https://numpy.org/doc/stable/) 
- [Matplotlib](https://matplotlib.org/stable/contents.html)  

## 1. Periodic and Quasi-Periodic Evolutions

### Equations Explored
The project investigates the behavior of three functions:
1. $$x_{t} = \cos(2t)$$
2. $$y_{t} = \cos(2t) + \sin(5t)$$
3. $$z_{t} = \cos(2t) + \sin(\pi t)$$

### Steps Taken
1. Graphed the evolution of each function with respect to time.
2. Plotted scatterplots of $u(t)$ vs $u[t+1]$ for each function.
3. Compared the behaviors of the functions.

## 2. Henón's Map

### Equations Explored
Henón's Map evolution is described by:
1. $$x_{t+1} = 1 - a \cdot x_{t}^2 + y_{t}$$
2. $$y_{t+1} = b \cdot x_{t}$$

### Steps Taken
1. Explored the invertibility and chaos potential of the map.
2. Found fixed points and their conditions for reality.
3. Programmed the Henón map in Python and visualized its evolution.

## 3. The Lotka-Volterra Model

### Equations Explored
The Lotka-Volterra model describes the interaction between rabbit and wolf populations:
1. $$\frac{dx}{dt} = αx - βxy$$
2. $$\frac{dy}{dt} = µxy - γy$$

### Steps Taken
1. Identified linearity, autonomy, and homogeneity of the system.
2. Interpreted equations and simplified parameters.
3. Calculated divergence of the vector field and analyzed behavior in phase space.
4. Found implicit solutions and fixed points of the system.
5. Calculated Jacobian, stability, and sketched orbits.
6. Numerically integrated the system and analyzed phase space.
7. Explored chaotic behavior potential and integrated the system accordingly.

---

## Conclusion

This project provides insights into the dynamics of various nonlinear systems, including periodic, quasi-periodic, and chaotic behaviors. By employing numerical methods and visualization techniques, we gain a deeper understanding of the underlying principles governing these systems.

For detailed instructions and code implementation, refer to the respective sections in the Jupyter Notebook or Python script provided.