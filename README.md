# Incremental Algorithm and Gauss Reduction Algorithm for Simplicial Complexes

This repository contains Python implementations of the **Incremental Algorithm** and **Gauss Reduction Algorithm** for computing the Betti numbers of a simplicial complex. The input can be either a simplicial complex (as a list or dictionary) or a filtration of subcomplexes.

## **Overview**

The project focuses on computing the **Betti numbers** of a simplicial complex, which are topological invariants that describe the number of holes in different dimensions. The algorithms implemented are:

1. **Incremental Algorithm**: Computes the Betti numbers by incrementally adding simplices and updating the boundary matrix.
2. **Gauss Reduction Algorithm**: Reduces the boundary matrix to its reduced form, which is used in the Incremental Algorithm.
