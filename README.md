# Resolution of the cylindrical pressure vessel problem

In this repository we will show the resolution of a classical problem in linear elasticity: we want to analyze the effects of an internal and external pressure distribution on a hollow cylinder, with an internal radius *a* and an external radius *b*.
We first achieved the solution using a FEM simulation software, then we compared it with the exact algebraic solutions (obtainable for this particular case). In the following sections we will show the steps that led us to the implementation of the problem, which required a strong theoretical background, from the mathematical model to the linear elasticity equations, along with a brief digression of the FEM method.

## Analitical approach

[This paper](https://github.com/marcomonte22/Pressure-vessel-COMSOLE-simulation/blob/35d51f33f89fdcc1593316fbc23df2cb0a73850e/analitical_solution.pdf) shows the derivation of the algebraic solution of the problem, using the principles of linear elasticity. 
The geometry of the problem can be visualized in the figure below. 

<img src = "cylinder pressure.png" alt = "pressure distribution and dimensions" width = "350">


## Numerical approach

In order to solve the problem numerically we implemented a structural simulation on COMSOL® using the weak formulation of the elastostatic problem. Here are listed some papers about a mathematical background on the variational calculus, the weak formulation and the finite element method:
* [variational calculus](https://github.com/marcomonte22/Pressure-vessel-COMSOLE-simulation/blob/cd715fedaba7105e907eb456e4e37c95c5a3c319/variational_calculus_background.pdf)
* [weak formulation of the elastostatic problem](https://github.com/marcomonte22/Pressure-vessel-COMSOLE-simulation/blob/cd715fedaba7105e907eb456e4e37c95c5a3c319/linear_elasticity.pdf)
* [finite element method](https://github.com/marcomonte22/Pressure-vessel-COMSOLE-simulation/blob/cd715fedaba7105e907eb456e4e37c95c5a3c319/fem_method.pdf)

[Here](https://github.com/marcomonte22/Pressure-vessel-COMSOLE-simulation/blob/09e062c9c0dc3ee07a961803ba0127ad8dc91d5a/comsole_implementation%20(1).pdf) you can find an interesting description of the methods used to implement the simulation on COMSOL®, with a detailed comparison with the solution obtained analitically.

### Conclusions

We have verified that the solutions obtained either numerically or algebraically, in
fact, do correspond. Over the course of the project, we acquired a good knowledge
of the COMSOL® software, which, with its versatility, can allow us to implement a
large variety of problems, starting from weak form PDE. However, a deep understanding 
of this software wouldn’t have been possible without a strong theoretical
basis. Our special thanks go to Dott. Matteo Ruggieri, who helped us with his
lectures and his support, and to Prof. Giuseppe Tomassetti, the supervisor of the
laboratory.

## Bibliography

* Lallit Anand, Sanjay Govindjee, Continuum Mechanics of Solids, Oxford University Press, 2020;
* Paolo Casini, Marcello Vasta, Scienza delle Costruzioni, Città Studi, 2019
* Matteo Ruggieri, Variational Formulation; Principle of Minimum Potential Energy and Elastostatic Systems, Università degli Studi Roma Tre, 2023;
* COMSOL® Documentation and COMSOL® Discussion Forum;





