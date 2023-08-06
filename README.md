# InverseDirac
Inversion of a Dirac Matrix

In lattice calculations, often the following problem appears: An ensemble of configurations of gauge field U(x) have been generated. To calculate an observable of interest, a certain matrix, which depends on the gauge fields, needs to be inverted and applied to a given vector. Here, we will look at the following simpliefied setting:

Considering a 2 dimensional square lattice of size N1xN2 as a discretization of a 1+1 dimensional space time. A fermion field is discretized in such a way that the field values are specified at each lattice point. Furthermore, an abelian gauge field is introduced at the links between neighboring lattice sites.

This abelian gauge field consists of complex number with absolute square 1. That is, the link between the lattice site x and the neighboring site in the direction μ, x+μ_hat, is called U(x) and has the form U(x) = exp(ia(x)), where a(x) is a real number.

![image](https://github.com/dhruvpatel09/InverseDirac/assets/28999393/2c4b21d0-2859-45c9-a915-b5fe5c5ed91c)

The task is now to consider the following matrix:
![image](https://github.com/dhruvpatel09/InverseDirac/assets/28999393/e565dd0d-d1e9-437c-8b66-629310686567)

Here, x and y are indices that denote lattice points and x+μ is the index of the neighboring lattice point to x in the μ direction. Furthermore, we assume antiperiodic boundary. That means that we assume periodic boundary conditions but multiply each term in which the periodicity is used by -1.
