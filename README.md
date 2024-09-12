# Implementation of Differential Evolution and Particle Swarm Optimization Algorithms

This repository contains implementations of Differential Evolution (DE) and Particle Swarm Optimization (PSO) algorithms applied to 8 benchmark optimization functions:

- High Conditioned Elliptic Function
- Bent Cigar Function
- Discus Function
- Rosenbrock’s Function
- Ackley’s Function
- Weierstrass Function
- Griewank’s Function
- Rastrigin’s Function

## Control Parameter Settings

### Differential Evolution (DE)
- **Population Size (Np):** 100
- **Crossover Probability (Cr):** 0.9
- **Scaling Factor (F):** 0.8
- **Scheme:** Canonical scheme: DE/bin/1

### Particle Swarm Optimization (PSO)
- **Population Size (Np):** 100
- **Cognitive Coefficient (C1):** 2.05
- **Social Coefficient (C2):** 2.05
- **Inertia Weight (W):** Linearly decreasing from 0.9 to 0.4
- **Maximum Velocity (v_max):** 0.1 * (x_max - x_min)
- **Minimum Velocity (v_min):** -v_max

### Problem Settings
- **Dimensions (D):** 2, 10, 20
- **Variable Range:** [-10, 10]
- **Number of Runs:** 31
- **Termination Condition:** Max_NFC = 3000 * D

## Comparison of DE and PSO Algorithms

Below is a comparison of the DE and PSO algorithms across the benchmark functions:

<div align="center">
    <img src="./images/comparison.png" alt="Comparison of DE and PSO D2" style="width: 80%; height: auto; margin-bottom: 10px;" />
    <img src="./images/comparison2.png" alt="Comparison of DE and PSO D10" style="width: 80%; height: auto; margin-bottom: 10px;" />
    <img src="./images/comparison3.png" alt="Comparison of DE and PSO D20" style="width: 80%; height: auto;" />
</div>

## Visualization of DE and PSO Algorithms on Benchmark Functions (D=2)

### High Conditioned Elliptic Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/Elliptic_DE.png" alt="DE Population on Elliptic Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/Elliptic_PSO.png" alt="PSO Population on Elliptic Function" style="width: 45%; height: auto;" />
</div>

### Bent Cigar Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/BentCigar_DE.png" alt="DE Population on Bent Cigar Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/BentCigar_PSO.png" alt="PSO Population on Bent Cigar Function" style="width: 45%; height: auto;" />
</div>

### Discus Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/Discus_DE.png" alt="DE Population on Discus Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/Discus_PSO.png" alt="PSO Population on Discus Function" style="width: 45%; height: auto;" />
</div>

### Rosenbrock’s Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/Rosenbrock_DE.png" alt="DE Population on Rosenbrock’s Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/Rosenbrock_PSO.png" alt="PSO Population on Rosenbrock’s Function" style="width: 45%; height: auto;" />
</div>

### Ackley’s Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/Ackley_DE.png" alt="DE Population on Ackley’s Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/Ackley_PSO.png" alt="PSO Population on Ackley’s Function" style="width: 45%; height: auto;" />
</div>

### Weierstrass Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/Weierstrass_DE.png" alt="DE Population on Weierstrass Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/Weierstrass_PSO.png" alt="PSO Population on Weierstrass Function" style="width: 45%; height: auto;" />
</div>

### Griewank’s Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/Griewank_DE.png" alt="DE Population on Griewank’s Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/Griewank_PSO.png" alt="PSO Population on Griewank’s Function" style="width: 45%; height: auto;" />
</div>

### Rastrigin’s Function 
###### DE | PSO

<div style="display: flex; justify-content: center;">
    <img src="./images/Rastrigin_DE.png" alt="DE Population on Rastrigin’s Function" style="width: 45%; height: auto; margin-right: 10px;" />
    <img src="./images/Rastrigin_PSO.png" alt="PSO Population on Rastrigin’s Function" style="width: 45%; height: auto;" />
</div>
