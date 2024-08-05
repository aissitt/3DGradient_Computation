# 3D Gradient Computation Benchmark

This project benchmarks gradient computation of 3D velocity data on both CPU and GPU using NumPy and CuPy. The goal is to validate and compare the performance between CPU and GPU implementations.

## Features

- Compute gradients of 3D velocity data on CPU using NumPy.
- Compute gradients of 3D velocity data on GPU using CuPy.
- Measure execution time and memory usage.
- Visualize performance results.

## Requirements

To run this project, you need the following dependencies:

- Python 3.6+
- NumPy
- CuPy
- Matplotlib
- PyCUDA
- Memory Profiler (for further testing)

You can install these dependencies using pip:

```bash
pip install numpy cupy matplotlib pycuda
