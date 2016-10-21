`nlmixr` is an R package for fitting general dynamic models, pharmacokinetic (PK) models and pharmacokinetic-pharmacosynamic (PKPD) models in particular, with either individual data or population data. `nlmixr` has five main modules:  1) `dynmodel()` and its mcmc cousin `dynmodel.mcmc()` for nonlinear dynamic models of individual data; 2) `nlme_lin_cmpt()`for one to three linear compartment models of population data with first order absorption, or i.v. bolus, or i.v. infusion; 3) `nlme_ode()` for general dynamic models defined by ordinary differential equations (ODEs) of population data; 4) `saem_fit` for general dynamic models defined by ordinary differential equations (ODEs) of population data by the Stochastic Approximation Expectation-Maximization (SAEM) algorithm;  5) `gnlmm` for generalized non-linear mixed-models (possibly defined by ordinary differential equations) of population data by adaptive Gaussian quadrature algorithm. 

A few utilities to facicitate population model building are also included in `nlmixr`.

nlmixr development url: https://github.com/nlmixrdevelopment


