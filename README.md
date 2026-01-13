# nqs-quantum-chemistry-notes
## Overview

This repository contains implementation notes and numerical experiments
related to Neural Quantum States (NQS),
a machine-learning-based representation of quantum many-body wave functions.

The objective is to understand the correspondence between theoretical
formulations and the numerical behavior of NQS within the context of
established quantum-chemical and quantum-mechanical frameworks.

In addition to theoretical considerations, particular emphasis is placed on hands-on implementation,
with attention to code structure, numerical diagnostics, and reproducible evaluation.

## Motivation

While NQS has attracted attention due to its expressive power,
its position relative to established quantum chemistry methods
(e.g., Hartree–Fock, configuration interaction, variational approaches)
remains an active topic of discussion.

Due to its high expressive flexibility, NQS is often discussed in the context
of strongly correlated systems, where conventional single-reference
approaches may become inadequate.
At the same time, this flexibility makes careful evaluation of numerical
stability, convergence, and physical consistency particularly important.

This project examines NQS as a variational wave function ansatz,
with a focus on numerical stability, convergence behavior, and
consistency with known physical constraints,
emphasizing careful evaluation within established
quantum-chemical methodologies.

## Scope of Implementation

- Basic NQS models implemented using Python and PyTorch
- Variational Monte Carlo–based energy optimization
- Examination of training stability and convergence behavior
- Comparison with reference results for small benchmark systems

The implementation is intentionally kept simple and transparent
to facilitate interpretability and verification.

## Key Points of Evaluation

- Variational behavior and energy convergence
- Dependence on initialization and hyperparameters
- Reproducibility of numerical results
- Relation to conventional variational wave function frameworks

## Notes

This repository serves as a supplementary learning record.
