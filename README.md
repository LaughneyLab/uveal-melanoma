# uveal-melanoma

Bakhoum MF*, Francis JH*, Agustinus A, Earlie EM, Di Bona M, Abramson DH, Duran M, Masilionis I, Molina E, Shoushtari AN, Goldbaum MH, Mischel PS, Bakhoum SF, Laughney AM. Loss of Polycomb Repressive Complex 1 activity and chromosomal instability drive uveal melanoma progression.
Nature Communications 12, 5402 (2021). https://doi.org/10.1038/s41467-021-25529-z

\* Authors contributed equally to this study.

Data Access:    https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE160883

Lab Website: https://laughneylab.com/

## Overview
The uveal-melanoma repository contains the code used for the single cell data analysis of the tumor cell subpopulations for the uveal melanoma study. This analysis includes 6 primary tumor samples from patients at MSK, along with an independent cohort of 8 primary tumor samples from [*Durante et al*](https://www.nature.com/articles/s41467-019-14256-1). A brief analysis was also performed on the reference cohort of 80 primary uveal melanoma sample from the TCGA study. 


## Dependencies
### uvmel_tumorcells_v4.ipynb:
  1. Python 3
  2. Jupyter Notebooks
  3. R-4.0.2
  4. R for Juypter Notebooks
  5. The uvmel Docker image


# Guide
The uvmel_tumorcells_v4.ipynb notebook is the Python notebook used for the main analyses and figure generation. This notebook can be run within a container spun from the uvmel Docker image.
