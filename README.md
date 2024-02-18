# HPC Benchmark Repository

This repository contains a collection of High-Performance Computing (HPC) benchmarks, focusing on evaluating the performance of supercomputers and parallel computing systems. The benchmarks cover various aspects of HPC, including computational speed, memory bandwidth, and data-intensive processing.

## Benchmarks Included

### 1. LINPACK Benchmark
- **Description**: Measures the floating-point computing power, primarily for solving linear equations. Basis for the TOP500 list.
- **Useful for**: Evaluating peak computational performance.

### 2. High Performance Conjugate Gradients (HPCG)
- **Description**: Complements LINPACK by testing performance on a broader set of computational tasks, including sparse matrix operations.
- **Useful for**: Assessing performance on real-world applications.

### 3. NAS Parallel Benchmarks (NPB)
- **Description**: Developed by NASA, evaluates the performance of parallel supercomputers using various tests, including computational fluid dynamics simulations.
- **Useful for**: Benchmarking parallel computing systems with MPI and OpenMP.

### 4. STREAM Benchmark
- **Description**: Measures sustainable memory bandwidth and computation rate for simple vector kernels.
- **Useful for**: Assessing the memory subsystem performance.

### 5. Graph500
- **Description**: Focuses on data-intensive workloads and evaluates performance in processing large graphs.
- **Useful for**: Benchmarking systems for applications in cybersecurity, medical informatics, and social network analysis.

### 6. SPEC MPI2007
- **Description**: A suite of benchmarks to evaluate the performance of MPI implementations on parallel systems.
- **Useful for**: Standardized benchmarking of MPI performance.

### 7. SPEC OMP2012
- **Description**: Designed to assess the performance of systems using OpenMP for shared-memory parallelism.
- **Useful for**: Benchmarking OpenMP performance.

### 8. LULESH (Livermore Unstructured Lagrangian Explicit Shock Hydrodynamics)
- **Description**: A proxy application that simulates hydrodynamics, used to evaluate performance in handling complex physics calculations.
- **Useful for**: Testing HPC systems on physics-based simulations.

## Usage

Each benchmark directory contains source code, documentation, and instructions for compilation and execution. Please refer to the individual README files within each benchmark directory for detailed usage information.

## Contributing

Contributions to this repository are welcome. Please submit a pull request or open an issue to suggest improvements or add new benchmarks.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
