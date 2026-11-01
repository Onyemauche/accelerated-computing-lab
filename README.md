# Accelerated Computing Lab

A hands-on engineering laboratory exploring CPU computing, GPU acceleration, parallel processing, and performance optimization using Python and PyTorch.

This project documents practical accelerated computing experiments, benchmarks, technical explanations, and performance analysis.

## Project Overview

Modern computing applications increasingly rely on accelerated hardware to process large amounts of data efficiently.

Traditional CPU-based computing is suitable for general-purpose tasks, while GPUs can execute many operations in parallel, making them useful for workloads such as numerical computing, scientific simulations, machine learning, image processing, and artificial intelligence.

The goal of this laboratory is to understand these technologies through practical experiments rather than theory alone.

We will implement computational workloads, execute them on available hardware, compare performance, validate results, and document our findings.

## Project Objectives

- Understand the fundamentals of accelerated computing.
- Explore CPU architecture and GPU architecture.
- Learn parallel computing concepts.
- Develop practical Python applications using PyTorch.
- Compare CPU and GPU execution performance.
- Understand GPU memory and data transfers.
- Measure computational speedup.
- Visualize benchmark results.
- Explore applications of accelerated computing in AI, scientific computing, and engineering.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| PyTorch | Tensor computation and hardware acceleration |
| CUDA | GPU computing on supported NVIDIA hardware |
| Google Colab | Browser-based development and experimentation |
| NumPy | Numerical computing and data handling |
| Matplotlib | Data visualization |
| GitHub | Source code and experiment documentation |

## Development Environment

The project uses a browser-first development approach.

Google Colab will provide an environment for writing and executing Python notebooks without requiring a local GPU.

The experiments should support CPU execution. GPU execution will be used when compatible hardware is available.

GPU availability depends on the computing environment and its resource allocation.

## Laboratory Experiments

### Experiment 01: CPU vs GPU Benchmarking

**Status:** In progress

The first experiment investigates the performance differences between CPU and GPU computing using matrix multiplication.

We will:

1. Generate numerical matrices of different sizes.
2. Perform matrix multiplication using the CPU.
3. Perform equivalent matrix multiplication using an available GPU.
4. Measure execution time.
5. Validate that both devices produce equivalent numerical results.
6. Calculate GPU speedup relative to CPU execution.
7. Visualize benchmark results.

**Performance metrics:**

- CPU execution time.
- GPU execution time.
- GPU speedup.
- Matrix dimensions.
- Numerical correctness.
- Hardware information.

### Experiment 02: Parallel Computing Fundamentals

**Status:** Planned

Explore parallel computation and understand how workloads can be divided into smaller operations that execute concurrently.

### Experiment 03: GPU Memory and Data Transfers

**Status:** Planned

Investigate GPU memory, memory allocation, host-to-device transfers, and device-to-host transfers.

### Experiment 04: Image Processing Acceleration

**Status:** Planned

Explore computational image-processing operations and investigate how GPU acceleration can improve processing performance.

### Experiment 05: Machine Learning Acceleration

**Status:** Planned

Use PyTorch to explore tensor operations and neural network computation on available hardware.

### Experiment 06: Engineering and Scientific Computing

**Status:** Planned

Explore numerical methods, simulations, and engineering-related computational workloads.

## Repository Structure

The project will gradually develop into the following structure:

```text
accelerated-computing-lab/
│
├── README.md
│
├── notebooks/
│   ├── 01_cpu_vs_gpu_benchmark.ipynb
│   ├── 02_parallel_computing.ipynb
│   ├── 03_gpu_memory_and_transfers.ipynb
│   ├── 04_gpu_image_processing.ipynb
│   ├── 05_machine_learning_acceleration.ipynb
│   └── 06_engineering_computing.ipynb
│
├── results/
│   ├── benchmarks/
│   ├── charts/
│   └── experiment-notes.md
│
├── docs/
│   ├── project-overview.md
│   ├── computing-fundamentals.md
│   ├── cpu-vs-gpu.md
│   ├── parallel-computing.md
│   ├── gpu-memory.md
│   └── benchmark-methodology.md
│
└── LICENSE
```

Note: This is the planned repository structure. Files and folders will be created progressively as experiments are implemented.

## Benchmarking Methodology

Reliable performance comparisons require consistent testing conditions.

The laboratory will follow these principles:

- Use equivalent computational workloads on both devices.
- Record hardware and software information.
- Use multiple repetitions to reduce measurement variability.
- Warm up GPU operations before measuring execution time.
- Account for asynchronous GPU execution when measuring performance.
- Distinguish computation time from data-transfer time.
- Validate numerical results.
- Document limitations and observations.

Performance results will be recorded from actual experiments. No benchmark values
