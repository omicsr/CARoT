
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Centralised and Automated Reporting Tools <img src="man/figures/carot.png" align="right" width="120" />

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![GitHub
tag](https://img.shields.io/github/tag/omicsr/CARoT.svg?label=latest%20tag)](https://github.com/omicsr/CARoT)
[![Coverage Status
(codecov)](https://codecov.io/gh/omicsr/CARoT/branch/master/graph/badge.svg)](https://codecov.io/gh/omicsr/CARoT)
<!-- badges: end -->

## Installation

``` r
# Install CARoT from CRAN:
install.packages("CARoT")

# Or the the development version from GitHub:
# install.packages("remotes")
remotes::install_github("omicsr/CARoT")
```

## Overview

*CARoT* (Centralised and Automated Reporting Tools) is an under
development set of Quality-Control reporting tools and some other
functions.

Currently *CARoT* includes the following functions:

  - `estimate_ethnicity()` allows to format VCF files and compute the
    genomic components (and some figures) for ethnicity.
  - `ggheatmap()` allows to compute heatmap with dendrogram on x-axis
    and y-axis using [ggplot2](https://ggplot2.tidyverse.org/).
  - `read_idats()` allows to efficiently import idats files mostly using
    [minfi](https://doi.org/doi:10.18129/B9.bioc.minfi) functions.
  - `pca_report()` allows to compute an analysis report using principal
    component analysis from
    [flashpca](https://github.com/gabraham/flashpca) tool.  
    The function can be used in a chunk within a Rmarkdown
    document/script with `results="asis"` to render the report.
  - `qc_idats()` allows to compute quality-control of methylation array
    from Illumina using a [rmarkdown
    template](https://github.com/mcanouil/CARoT/blob/master/inst/rmarkdown/qc_idats.Rmd).
  - `qc_plink()` allows to compute quality-control of genotyping array
    (PLINK format) using a [rmarkdown
    template](https://github.com/mcanouil/CARoT/blob/master/inst/rmarkdown/qc_plink.Rmd).
  - `qc_impute()` allows to compute post-imputation quality-control
    report using a default [rmarkdown
    template](https://github.com/mcanouil/CARoT/blob/master/inst/rmarkdown/qc_impute.Rmd).
  - `mist()` allows to test for association between a set of SNPS/genes
    and continuous or binary outcomes by including variant
    characteristic information and using (weighted) score statistics.

## Getting help

If you encounter a clear bug, please file a minimal reproducible example
on [github](https://github.com/omicsr/CARoT/issues).  
For questions and other discussion, please contact the package
maintainer.

-----

Please note that this project is released with a [Contributor Code of
Conduct](.github/CODE_OF_CONDUCT.md).  
By participating in this project you agree to abide by its terms.
