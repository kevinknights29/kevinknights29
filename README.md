# Kevin Knights

### Computational Mathematics & Scientific Computing

I build high-performance numerical software for mathematically demanding problems.

I am completing an MSc in **High-Performance Computing (Computational Mathematics)** at Trinity College Dublin’s School of Mathematics. My current interests include numerical linear algebra, sparse linear system solvers, Krylov subspace methods, and GPU-accelerated scientific computing.

Before specializing in computational mathematics, I spent five years building production machine learning and data systems at Dell Technologies and AES. That experience shaped how I approach research software: mathematical ideas should lead to efficient, reliable implementations that work at realistic scale.

## Research

### [Communication-Avoiding Krylov Exponential Integration for Multi-GPU Option Pricing](https://github.com/kevinknights29/caksm)

My MSc thesis, supervised by **Prof. Kirk M. Soodhalter**, investigates when communication-avoiding Krylov methods can outperform conventional approaches in distributed multi-GPU environments.

The principal contribution is a **dimensionless regime map** that predicts whether communication avoidance should pay on a given machine using problem parameters and independently calibrated machine constants—before running the full implementation.

The model correctly predicted:

- No benefit on a single-NUMA-node CPU
- A benefit across four NVIDIA V100 GPUs on two nodes
- A **1.78–1.80x speedup** over an equal-work control

## Research interests

- Numerical linear algebra
- Sparse linear system solvers
- Krylov subspace methods
- Matrix functions and exponential integrators
- GPU and multi-GPU computing
- Communication-avoiding algorithms
- Performance modeling and optimization
- Numerical methods for computational finance
- Efficient training and inference of machine learning models

## Technical focus

- **Languages:** Python and C++
- **Parallel computing:** CUDA, MPI, OpenMP, and NCCL
- **Scientific computing:** numerical simulation, sparse linear algebra, and performance analysis
- **Machine learning:** production ML systems, model deployment, distributed data processing, and inference optimization

## Connect

I am interested in research and engineering conversations at the intersection of mathematics, high-performance computing, and machine learning.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kevin%20Knights-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevinknights/)
[![Email](https://img.shields.io/badge/Email-kevin.k.knights%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:kevin.k.knights@gmail.com)

---

*"What is the fruit of these teachings? Only the most beautiful and proper harvest of the truly educated——tranquillity, fearlessness, and freedom. We should not trust the masses who say only the free can be educated, but rather the lovers of wisdom who say that only the educated are free."* ~ Epictetus.
