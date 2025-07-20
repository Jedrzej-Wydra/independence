# Distance of Mean Embedding for Testing Independence of Functional Data

#### authors: Mirosław Krzyśko, Łukasz Smaga, Jędrzej Wydra

## Short summary (of Jędrzej’s contribution)
Developed advanced independence tests for functional data by implementing kernel-based mean embedding measures, permutation-based inference, and basis expansion techniques in Python and R. Optimized simulation pipelines, parallel computations, and GPU acceleration for high-dimensional data scenarios.

## Technical summary (of Jędrzej’s contribution)
Implemented novel independence testing procedures for functional data using distance of mean embedding (DIME/tDIME) with marginal, asymmetric, and symmetric aggregation. Built robust simulation frameworks with Fourier and B-spline basis expansions, permutation tests, and kernelized measures in Python (PyTorch, scikit-fda) and R (fda, doParallel). Designed GPU-accelerated workflows for large-scale Monte Carlo experiments and validated performance against distance covariance and HSIC. Integrated basis smoothing, resampling, and high-performance parallelization to evaluate type I error control and test power on real-world functional datasets.

## Abstract
We investigate independence testing for functional data, which may be either univariate or multivariate. Broadly speaking, our approach involves first reducing the dimensionality of the functional data using basis expansion and then applying the distance of mean embedding - a flexible measure of independence. We enhance this method for pairwise independence by incorporating marginal aggregation, as well as asymmetric and symmetric aggregation measures, to improve test performance and adapt it to mutual independence testing. Our methods are compared with tests based on distance covariance and the Hilbert-Schmidtindependence criterion. To evaluate their effectiveness, we present simulation studies and two real data examples using air pollution and chemometric data sets. The new testing procedures demonstrate favorable finite-sample properties, effectively controlling the type I error rate and exhibiting competitive power, making them viable alternatives to covariance-based tests.

## Preprint and full text hyperlinks
You can access the preprint here: [Distance of Mean Embedding for Testing Independence of Functional Data (SSRN)](https://dx.doi.org/10.2139/ssrn.5019416).

You can access the full text here: [Distance of Mean Embedding for Testing Independence of Functional Data (Signal Processing)](https://doi.org/10.1016/j.sigpro.2025.109959).

## History
This project is truly a dream come true for me — it’s all about developing a new test for the independence of functional data. But, of course, with great dreams come great challenges. First, designing new statistical tests is no walk in the park; it’s more like navigating a maze in the dark. Second, functional data is notoriously tricky — working with it feels like trying to solve a puzzle where the pieces keep changing shape. Despite these hurdles, I’m thrilled to tackle this project, knowing that if it succeeds, it could make a significant impact in the field.

## Discalimer
Due to data-sharing policies and project restrictions, I can only share selected parts of the Python scripts used in this study. The full datasets and complete scripts cannot be provided without the project leader’s permission. All analyses were conducted in R and Python following the team’s guidelines.

