# Portfolio Optimization with Quantum and Classical Methods

A quantum computing project exploring portfolio optimization using QAOA (Quantum Approximate Optimization Algorithm) and VQE (Variational Quantum Eigensolver), compared with classical approaches.

## Overview

This project implements and compares quantum and classical methods for portfolio optimization:

- **Classical optimization** using standard algorithms
- **QAOA** for quantum approximate optimization
- **VQE** for variational quantum eigensolver
- Analysis in both **noiseless** and **noisy** environments

## Prerequisites

- Python 3.8+
- Jupyter Notebook
- Qiskit
- NumPy
- Matplotlib
- Pandas

## Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/hssuryawanshib23-afk/Portfolio-Optimization.git
    cd Portfolio-Optimization
    ```

2.  Install required packages:

    ```bash
    pip install qiskit numpy matplotlib pandas jupyter
    ```

## Project Structure

```
src/
├── noise/                  # Noisy quantum simulations
│   ├── qaoa_solution.ipynb
│   └── vqe_solution.ipynb
└── noiseless/              # Ideal quantum simulations
    ├── classical_solution.ipynb
    ├── qaoa_solution.ipynb
    ├── vqe_solution.ipynb
    └── plots.ipynb
```

## Usage

### Running Classical Solution

```bash
cd src/noiseless
jupyter notebook classical_solution.ipynb
```

### Running QAOA (Noiseless)

```bash
cd src/noiseless
jupyter notebook qaoa_solution.ipynb
```

### Running QAOA (With Noise)

```bash
cd src/noise
jupyter notebook qaoa_solution.ipynb
```

### Running VQE (Noiseless)

```bash
cd src/noiseless
jupyter notebook vqe_solution.ipynb
```

### Running VQE (With Noise)

```bash
cd src/noise
jupyter notebook vqe_solution.ipynb
```

### Generating Plots

```bash
cd src/noiseless
jupyter notebook plots.ipynb
```

## Methods

### Classical Optimization

Standard portfolio optimization using classical algorithms to establish baseline performance.

### QAOA (Quantum Approximate Optimization Algorithm)

Quantum algorithm that alternates between problem and mixing Hamiltonians to find approximate solutions.

### VQE (Variational Quantum Eigensolver)

Hybrid quantum-classical algorithm that uses a parameterized quantum circuit to find the ground state energy.

## Results

The project compares:

- Solution quality across different methods
- Impact of quantum noise on optimization
- Computational efficiency
- Convergence behavior

## License

MIT License

## Author

Harsh Suryawanshi
