# Dissertation: Informative censoring models for liver transplantation data

Code Appendix


This repository supports the analysis of the project 'Informative censoring models for liver transplantation data' by Despina Konstantinidou for the degree of MSc Data Science & Statistics of the University of Bath.

The National Health Service of Blood and Transplant (NHSBT) permitted the liver transplantation data to the supervisor of the project, Dr Karim Anaya-Izquierdo, for research and academic purposes. However, access to the data is limited, and it cannot be available in public.

The main files are the following:

* 'optimisation.Rmd' is the R markdown file for the non-covariate model estimates optimisation. This file includes the corresponding log-likelihood and gradient functions to support the analysis.

* 'optimisation-covariates.Rmd' is the R markdown file for the covariate model estimates optimisation, respectively.

* 'non_informative_censoring.Rmd' is  the R markdown file for the non-informative regression models using `flexsurv`

The codes from in the first two files run multiple iterations, and thus the running time is very long. We only provide the code since the outputs require extra permission.

