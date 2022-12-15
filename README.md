# Estimating retirement benefit elasticity
Code to implement structural models of retirement benefits

The goal of this repo is to implement dynamic models of retirement decisions, in particular [Stock and Wise](https://www.jstor.org/stable/2938304). Code for this model in fortran can be found [here](https://www.journals.uchicago.edu/doi/suppl/10.1086/686263#). This repository includes a python implementation of the model

## Background

There are multiple models considered to estimate retirement elasticity some are more reduced form than others
* [Coile and Gruber](https://direct.mit.edu/rest/article/89/2/234/57676/Future-Social-Security-Entitlements-and-the) is a more reduced form option.
* There are more structural versions of the model that solve via dynamic programming, like [this](https://www.rand.org/pubs/research_reports/RR1503.html). 
 
## Code
Starting with implementation of a different implementation dynamic programming with backward recursion and will build on it. Currently there is not much here.
