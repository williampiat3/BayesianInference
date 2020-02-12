# Bayesian Inference
Here I am presenting different approaches for making bayesian inference: from Monte Carlo method to the parametric approach like variational inference they allow to approximate the distributions of our parameters given the data

We are often trying to find the best set of values of a parametrizable function or model, however there are some uncertainties on the inputs, some uncertainties on the output. In that case we would like to know not only the optimum value but the distribution of the values. For instance some parameters might have multiple modes: multiple values that give the same satisfactory result, however the mode that is the most stable (gives a reduced variance of the output) can be more satisfactory.

Monte Carlo Markov Chains can be used to sample from the posterior meaning the distribution that takes into account the data.

In case of numerous parameters, insuring the convergence of the Markov chains takes a lot of time to converge, some extensions of the methods can be made to scale to a larger number of parameters. However in case of a higher number of parameters some methods other methods can be used to approximate these distributions

## Introduction
The first notebook will present the basic of MCMC and simple cases to present the power of such methods

## Scaling up MCMC
The second notebook will present extension on how to improve the simple MCMC so as to compute more efficiently the distributions

## Variational inference for approximating posterior distributions
The third notebook is a presentation of variationnal inference, the classic approaches, the packages dedicated to it and how they can be useful to scale up our computations
