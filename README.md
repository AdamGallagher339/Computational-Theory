# Computational Theory Assessment — SHA-256 (FIPS 180-4)

This repository contains a Jupyter notebook implementing key components of the SHA-256 cryptographic hash function as defined in the Secure Hash Standard (FIPS 180-4). The goal of the project is to demonstrate a clear understanding of how SHA-256 operates internally by implementing its core primitives, message processing steps, and compression function directly in Python.

Rather than relying on a single library call, the algorithm is built step by step to reflect the structure of the standard and to highlight the role of bitwise operations, modular arithmetic, and message padding in cryptographic hashing.

---

## Contents

- `problems.ipynb`  
  Main notebook containing solutions to all five assessment problems:
  1. Binary word and bitwise operations used by SHA-256  
  2. Derivation of SHA-256 round constants from cube roots of primes  
  3. Message padding and 512-bit block parsing  
  4. SHA-256 compression function and end-to-end hashing  
  5. Dictionary attack on unsalted SHA-256 password hashes and security discussion  

- `requirements.txt`  
  Python dependencies required to run the notebook.

- `materials/`  
  Course-provided reference materials, including the Secure Hash Standard and supporting notebooks.

---

## Requirements

- Python 3.x  
- NumPy  

All required packages are listed in `requirements.txt`.

---

## Setup and Installation

### GitHub Codespaces (recommended)
This repository is compatible with GitHub Codespaces.

1. Open the repository in Codespaces.
2. Install dependencies (if not already installed):

```bash
pip install -r requirements.txt
