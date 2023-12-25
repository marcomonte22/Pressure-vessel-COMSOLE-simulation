# Resolution of the pressure vessel problem

In this repository we will show the resolution of classical problem in linear elasticity. We want to analyze the effects of an internal and external pressure distribution on an hollow cylinder, with an internal radius *a* and an external radius *b*.
We first achieved the solution using a FEM simulation software, then we compared it with the exact algebraic solutions (obtainable forthis particular case). In the following sections we will show the steps that led us to the implementation of the problem, which required a strong theoretical back-ground, from the mathematical model to the linear elasticity equations, along with a brief digression of the FEM method.

## Analitical approach

This paper shows the derivation of the algebraic solution of the problem, using the principles of linear elasticity. The geometry problem can be visualized in the figure below. 
<img src = "cylinder pressure.png" alt = "pressure distribution and dimensions" width = "350">


## Numerical approach

In order to solve the problem numerically we implemented a structural simulation on COMSOLE using the weak formulation of the elastostatic problem. Here are listed some papers about the mathematical background about the variational calculus, the weak formulation and the finite element method:
* variational calculus
* weak formulation of the elastostatic problem
* finite element method





