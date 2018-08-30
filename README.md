# scFeatureFilter
By Angeles Arzalluz-Luque, Guillaume Devailly, Anna Mantsoki & Anagha Joshi.

![scFeatureFilter outputs](inst/figure1_small.png)


An R package to set thresholds for feature (gene, transcript, ...) filtering in single cell RNA sequencing analyses.

# How to install?
You can install the stable version of scFeatureFilter from Bioconductor (Require R version ≥ 3.5):
```R
## try http:// if https:// URLs are not supported
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("scFeatureFilter")
```

You can install the development version of scFeatureFilter using `devtools` (Require R version ≥ 3.5):
```R
devtools::install_github("gdevailly/scFeatureFilter")
```

# Getting started
Load the package:
```R
library(scFeatureFilter)
```

Then it is probably a good idea to read the package [vignette](https://gdevailly.github.io/scFeatureFilterVignette.html):
```R
vignette("Introduction", package = "scFeatureFilter")
```
