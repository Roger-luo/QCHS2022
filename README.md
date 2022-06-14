# QCHS2022

## Installation & Setup

1. Install Julia
2. run the following in Julia REPL

```julia
pkg> instanitiate
julia> using IJulia; IJulia.notebook(dir=pwd())
```

## Day 1: The Yao ecosystem & variational quantum algorithms

- Introduction of Yao
- Implement Quantum Fourier Transform using Yao
- Understanding automatic differentiation of Yao

Pick one of the following:
1. find the corresponding U(4) gate parameter of given gate set
2. find the ground state of the following hamiltonian (Rydberg Hamiltonian) on a chain lattice using imaginary time evolution/eigensolver/VQE

$$
\sum \frac{V}{|r_i-r_j|^6} n_i n_j + \Omega \sum_i X_i - \Delta \sum_i n_i
$$

3. bounty issue (https://github.com/QuantumBFS/Yao.jl/issues/403)
4. explore other notebooks

## Day 2: The Rydberg system & Bloqade

- Introduction of Rydberg system & Bloqade
- Simulating adaiabtic evolution using Bloqade
- Solving maximum indenpendent set problem using Rydberg atom array (hands-on with unimplemented questions)

# License

MIT License
