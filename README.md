# Loop-Amplituhedron-Stratification

This repository contains the code used to reproduce the results presented in [your paper title]. It focuses on the stratification of the algebraic boundary of the 4-point, 2-loop Amplituhedron.

## Files and Descriptions

1. **`algebric_boundary_Stratification.m2`**:
   - Computes the stratification of the algebraic boundary of the 4-point, 2-loop Amplituhedron (see Definition 3.1 in the paper).
   - The representatives of the stratification, classified by codimension and symmetry group, are saved in files `Representatives1`, `Representatives2`, ..., `Representatives8`.

2. **Strata Classification**:
   - Strata are divided into two categories: **boundary** and **residual** strata.
   - The file **`real_strat_poset`** contains a list where each element is a sublist of all strata of the same codimension. These sublists are further split into two parts:
     - The first part contains the boundary strata.
     - The second part contains the residual strata.

3. **Boundary Definitions and Inequalities**:
   - A **boundary** is defined as the intersection of a boundary stratum with the Amplituhedron (see Definition 4.1 in the paper).
   - The inequalities describing these semi-algebraic sets can be computed using Maple's `LazyRealTriangularize` function. The analysis of the boundaries’ connected components can be performed using **Cylindrical Algebraic Decomposition (CAD)**.
   - The results of this analysis are contained in the Maple file **`RealTriag2loop.mv`**.

4. **Inclusion Relations**:
   - The inclusion relations between the boundary strata are computed in **`Loop_Amp_poset.m2`**.

## Additional Information

- Further technical details, including the logic and methodology behind each computation, are embedded within the code.
- Please refer to the paper for a comprehensive discussion of the theoretical framework.




