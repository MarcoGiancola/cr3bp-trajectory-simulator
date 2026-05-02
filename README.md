## **cr3bp-trajectory-simulator**
Python simulator for the Circular Restricted Three-Body Problem (CR3BP), integrating the Earth–Moon equations of motion to compute and visualize spacecraft trajectories from given initial conditions.

---

## **Project Overview**
This project provides a modern Python implementation of a numerical integrator for the Circular Restricted Three‑Body Problem (CR3BP) applied to the Earth–Moon system.
The goal is to compute and visualize spacecraft trajectories in the synodic (rotating) reference frame using compact, readable, and efficient Python code.

The project is inspired by work I carried out during my Mathematics thesis, where I used a Fortran 77 integrator (provided by my external advisor) to compute Earth–Moon transfer trajectories. That original program used a classical 4th‑order Runge–Kutta method and required MATLAB for visualization.
In this repository, I present a fully modernized Python version capable of integrating the equations of motion and plotting trajectories directly.

The notebook is organized into four main sections:

**1. Equations of Motion**  
Python implementation of the CR3BP equations in the synodic (rotating) reference frame.

**2. Numerical Integration**  
Use of SciPy’s solve_ivp function (adaptive Runge–Kutta method) to integrate the equations of motion.

**3. Trajectory Visualization**  
A plotting function that displays the spacecraft trajectory in the synodic frame, including the correct positions of Earth and Moon.

**4. Simulation Examples**  
Several test cases using different initial conditions expressed in nondimensional CR3BP units.

For additional background, see my article on the CR3BP (in Italian):
https://www.matematicamente.it/magazine/19aprile2013/184-Giancola-PR3C.pdf
