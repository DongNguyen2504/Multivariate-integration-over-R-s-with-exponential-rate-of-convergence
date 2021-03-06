# Multivariate-integration-over-R-s-with-exponential-rate-of-convergence
We analyze the approximation of multivariate integrals over the Euclidean space for functions which are analytic. We show explicit upper bounds which attain the exponential rate of convergence. We use an infinite grid with different mesh sizes in each direction to sample the function, and then truncate it. In our analysis, the mesh sizes and the truncated domain are chosen by optimally balancing the truncation error and the discretization error.

This is the source code for the numerical section of the paper "Nguyen, D. T. P., and Nuyens, D. Multivariate integration over $R^s$ with exponential rate of convergence. Journal of Computational and Applied Mathematics 315 (2017), 327–342."

In order to calculate with very high precision, our test are implemented in C++ using the Boost.Multiprecision library which allows us to define variables with arbitrary decimal digit precision.
