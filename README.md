# Emerging Technologies README

This README is a file that will provide you with context on my repository for the Emerging Technologies module.

## Overview

This repository contains solutions to a series of problems exploring both classical and quantum approaches to analysing Boolean functions. The work progresses from simple classical function generation to implementing full quantum algorithms using Qiskit.

The main focus of the assignment is to demonstrate how quantum computing can determine global properties of a function more efficiently than classical methods.

The problems are structured as follows:

## Problem Descriptions

### Problem 1: Generating Random Boolean Functions

A Python function is implemented to generate random Boolean functions that take four inputs. Each function is guaranteed to be either:

- Constant (always returns True or always returns False)
- Balanced (returns True for exactly half of the inputs and False for the other half)

---

### Problem 2: Classical Testing for Function Type

A classical method is developed to determine whether a given function is constant or balanced.

This section also includes an analysis of efficiency, showing that in the worst case, a classical algorithm may need to evaluate the function multiple times to be certain of the result.

---

### Problem 3: Quantum Oracles

Quantum oracles are constructed using Qiskit for all possible Boolean functions with a single input.

Each oracle is explained and demonstrated, showing how classical logic is encoded into a quantum circuit.

---

### Problem 4: Deutsch's Algorithm

Deutsch’s algorithm is implemented using Qiskit.

The circuit demonstrates how quantum interference allows us to determine whether a function is constant or balanced using only one evaluation of the oracle.

---

### Problem 5: Deutsch–Jozsa Algorithm

The Deutsch–Jozsa algorithm extends the previous idea to functions with multiple inputs.

In this project:

- A general quantum circuit is built for 4-bit inputs
- Classical functions are converted into quantum oracles
- The circuit is tested on both constant and balanced functions
- Results are analysed to confirm correctness

This demonstrates a key advantage of quantum computation over classical approaches.

---

## Technologies Used

- Python
- Qiskit
- NumPy
- Jupyter Notebook

---

## What is a Jupyter Notebook?

A Jupyter Notebook is an interactive environment where you can write and run code in small sections called cells.

It allows you to combine:

- Code
- Explanations written in Markdown
- Visual outputs such as graphs and circuit diagrams

This makes it especially useful for scientific computing and teaching, as it keeps code and explanations together in one place.

---

## How to Run the Code

### 1. Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/EmmanuellaOsikoya/emerging-technologies.git
```
Then move into the project folder:

```bash
cd emerging-technologies
```

### 2. Set Up a Python Environment

Before installing any packages, you will need a Python environment

You can use a virtual environment to keep dependencies organised:

```bash
python -m venv venv
```

To activate the environment you run the following:

On Windows:

```bash
venv\Scripts\activate
```

On macOS or Linux:

```bash
source venv/bin/activate
```

### 3. Install Required Packages

Once the environment is active install the required libraries by running the following command:

```bash
pip install -r requirements.txt
```

### 4. Launch the Assignment Notebook

Once the requirements have been installed, you can run the Jupyter Notebook by running the following command:

```bash
jupyter notebook problems.ipynb
```