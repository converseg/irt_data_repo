

ECPE data can also be downloaded via the CDM package in R, found at https://cran.r-project.org/web/packages/CDM/CDM.pdf.

The files for response sets are too large for this repository, but can be easily generated from the provided data.

To generate response sets:
For each student j with K latent traits T_j = [t_{j1}, ..., t_{jk}, ..., t_{jK}], and for each item i, calculate 
Pr(student j answers item i correctly) = 1/(1+ exp(-(sum_{k=1}^K a_{ik} t_{jk} - b_i)))
