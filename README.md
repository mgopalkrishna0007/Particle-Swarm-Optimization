# Particle-Swarm-Optimization

# Particle Swarm Optimization for Rosenbrock Function

This repository contains a MATLAB implementation of Particle Swarm Optimization (PSO) to find the optimal values for the Rosenbrock function, a commonly used test problem for optimization algorithms.

## Objective

The objective function \( Z \) is defined as:
\[
Z = (1 - x)^2 + 100 \times (y - x^2)^2
\]
where \( x \) and \( y \) are the variables to be optimized.

![image](https://github.com/user-attachments/assets/855bb925-6d99-4af1-b7f7-ec959b5c4c08)

## Implementation Details

- **Objective Function**: Rosenbrock function without constraints.
- **Algorithm**: PSO, iterating through candidate solutions and updating velocities and positions based on personal and global bests.
- **Parameters**:
  - Population size: `nPop = 100`
  - Maximum iterations: `MaxIter = 220`
  - Inertia weight: `w = 0.7`
  - Acceleration coefficients: `c1 = 1.2`, `c2 = 1.2`

## Plotting
After optimization, the code generates a 3D surface plot of the Rosenbrock function, with the optimal point found by PSO highlighted.

![Screenshot 2024-11-13 221151](https://github.com/user-attachments/assets/b4cbf81f-961a-41b4-bac5-3333cd28ae36)

## Usage

Run the script in MATLAB to execute the PSO algorithm and visualize the results.
