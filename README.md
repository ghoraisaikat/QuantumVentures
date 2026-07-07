# QuantumVentures

A collection of small quantum computing experiments and notebooks built using **Qiskit** and **PennyLane**. This repository contains implementations of fundamental quantum algorithms, entangled states, arithmetic circuits, and introductory variational quantum computing examples.

## Features

* Bell state generation
* Basic Qiskit "Hello World" example
* Ring entanglement circuits
* Quantum subtractor circuit
* Max-Cut Hamiltonian construction with PennyLane
* Sample parity dataset for VQC experiments

## Project Structure

```text
.
├── main.py
├── pyproject.toml
├── src
│   ├── bell_pl.ipynb
│   ├── hello_world.ipynb
│   ├── ring_entanglement.ipynb
│   ├── subtractor.ipynb
│   └── VQCs
│       ├── max_cut_hamiltonian.ipynb
│       └── parity_train.txt
```

## Requirements

* Python 3.14+
* Qiskit
* PennyLane
* Jupyter Notebook

Additional dependencies are listed in `pyproject.toml`.

## Installation

Clone the repository:

```bash
git clone https://github.com/ghoraisaikat/QuantumVentures/
cd quantumventures
```

Create a virtual environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate      # Linux/macOS
# .venv\Scripts\activate       # Windows
```

Install the project dependencies:

```bash
pip install .
```

or

```bash
pip install -e .
```

## Running

Verify your Qiskit installation:

```bash
python main.py
```

This prints the installed Qiskit version.

## Notebooks

| Notebook                         | Description                                                      |
| -------------------------------- | ---------------------------------------------------------------- |
| `hello_world.ipynb`              | Creates and simulates a Bell state using Qiskit.                 |
| `bell_pl.ipynb`                  | Bell state preparation using PennyLane.                          |
| `ring_entanglement.ipynb`        | Generates an n-qubit ring entanglement circuit.                  |
| `subtractor.ipynb`               | Implements an n-bit quantum subtractor using MAJ/UMA gates.      |
| `VQCs/max_cut_hamiltonian.ipynb` | Builds a Max-Cut Hamiltonian for variational quantum algorithms. |

## Technologies

* Qiskit
* Qiskit Aer
* PennyLane
* JAX
* Optax
* Matplotlib
* Scikit-learn
* Jupyter Notebook
