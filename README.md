# automatic-differentiation-random-effect-model
Computer codes implements the automatic differentiation for fitting zero-inflated negative binomial mixed regression model using ADMB and TMB, and generates the results in the simulation part of Shi (2018+) " Fast and Robust Fitting Random Effects Mixture Models using Automatic Differentiation with Application in Genomics", submitted to Scientific Reports.

The codes were run and tested on a machine with an Intel i7-3770k CPU processor and Ubuntu 16.04 operation system. There are two files included: an ADMB TPL file and an R file containing the R codes. Before running the codes, the following packages and other required packages for them need to be installed:

ADMB (version 11.5): http://www.admb-project.org/

TMB (version 1.7.11): https://github.com/kaskr/adcomp/wiki

The following R packages, R2admb, glmmTMB, doParallel, R.utils, pscl, from CRAN: https://cran.r-project.org/
