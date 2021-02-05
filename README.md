# qoqo-calculator-py03

Python interface to qoqo calculator, the calculator backend of the qoqo quantum computing toolkit by [HQS Quantum Simulations](https://quantumsimulations.de).

qoqo-calculator-py03 provides
* A calculator python class that evaluates symbolic string expressions to float values
* A CalculatorFloat python class that can represent a float value or a string based symbolic expression
* A CalculatorComplex python class that represents complex numbers where real and imaginary parts can be CalculatorFloat

This software is still in the beta stage. Functions and documentation are not yet complete and breaking changes can occur.

## Installation

This package can be installed directly from pypi using

```
pip install qoqo-calculator-pyo3
```

When building manually we recommend using [maturin](https://github.com/PyO3/maturin) to build the python package.