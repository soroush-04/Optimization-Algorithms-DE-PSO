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

| Dimension 2 | Dimension 10 | Dimension 20 |
|:--------------:|:---------------:|:---------------:|
| ![D2](./images/comparison.png)  | ![D10](./images/comparison2.png) | ![D20](./images/comparison3.png) |

## Visualization of DE and PSO Algorithms on Benchmark Functions (D=2)

### High Conditioned Elliptic Function

| DE | PSO |
|:----------------------------------:|:----------------------------------:|
| ![DE](./images/Elliptic_DE.png)    | ![PSO](./images/Elliptic_PSO.png)   |

### Bent Cigar Function

| DE | PSO |
|:-------------------------------------:|:-------------------------------------:|
| ![DE](./images/BentCigar_DE.png)    | ![PSO](./images/BentCigar_PSO.png)   |

### Discus Function

| DE | PSO |
|:--------------------------------:|:--------------------------------:|
| ![DE](./images/Discus_DE.png)    | ![PSO](./images/Discus_PSO.png)   |

### Rosenbrock’s Function

| DE | PSO |
|:---------------------------------------:|:---------------------------------------:|
| ![DE](./images/Rosenbrock_DE.png)      | ![PSO](./images/Rosenbrock_PSO.png)     |

### Ackley’s Function

| DE | PSO |
|:----------------------------------:|:----------------------------------:|
| ![DE](./images/Ackley_DE.png)      | ![PSO](./images/Ackley_PSO.png)     |

### Weierstrass Function

| DE | PSO |
|:-------------------------------------:|:-------------------------------------:|
| ![DE](./images/Weierstrass_DE.png)    | ![PSO](./images/Weierstrass_PSO.png)   |

### Griewank’s Function

| DE | PSO |
|:------------------------------------:|:------------------------------------:|
| ![DE](./images/Griewank_DE.png)      | ![PSO](./images/Griewank_PSO.png)     |

### Rastrigin’s Function

| DE | PSO |
|:-------------------------------------:|:-------------------------------------:|
| ![DE](./images/Rastrigin_DE.png)      | ![PSO](./images/Rastrigin_PSO.png)     |
