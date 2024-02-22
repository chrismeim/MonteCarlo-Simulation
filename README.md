# Monte Carlo Simulation
Monte Carlo Simulations for European and Asian (Exotic) Options

### Summary
Development of Monte Carlo simulations for 1000 iterations showcasing the accuracy of the method

### In Detail
In this Excercise I have developed various functions, aiming to capture the accuracy of Monte Carlo Simulations comperative to the BlackScoles model.

The way I have structured my analysis starts with developing a function called "BSM" that calculates the value of a European Call option based on the BlackScholes Model.
Furthermore, I plot the stochastic process z, in order to showcase that by obtaining a large dataset, z approximates the Standard Normal Distribution (as expected)
As a last step, I develop the function called "EuropeanCallPrice_MC" which calculates the value of the European Call based on the Monte Carlo simulation. Bellow we can see the accuracy of the model based on the number of iterations that we use.

The same process is followed for the Asian Option
