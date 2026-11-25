# %LGTPHCURV_CLUSTER
Placeholder repository for potentially hosting a modified version of the %LGTPHCURV9 SAS macro.

This SAS macro adds the ability to specify a robust sandwich covariance matrix (by passing the COVS(AGGREGATE) PROC PHREG option) to account for non-independence of observations due to clustering by shared NHSII moms in GUTS. %LGTPHCURV_CLUSTER accounts for clustering by the variable passed by the CLUSTER= option. No other changes are made to the macro. 

The original %LGTPHCURV9 macro was produced to assess "non-linear exposure-response relations and [produce] nice graphs for logistic and proportional hazards models" in SAS, and was released by Ruifeng Li, Ellen Hertzmark, Mary Louie, Linlin Chen, and Donna Spiegelman in July of 2011. 

A link to the original macro's details can be found here: https://ysph.yale.edu/cmips/research/software/analysis-graphics/lgtphcurv9/. 
