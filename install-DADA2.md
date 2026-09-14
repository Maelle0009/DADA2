R Notebook
================

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("dada2", version = "3.23")
```

    ## 'getOption("repos")' replaces Bioconductor standard repositories, see
    ## 'help("repositories", package = "BiocManager")' for details.
    ## Replacement repositories:
    ##     CRAN: https://p3m.dev/cran/__linux__/noble/latest

    ## Bioconductor version 3.23 (BiocManager 1.30.27), R 4.6.1 (2026-06-24)

    ## Installing package(s) 'BiocVersion', 'dada2'

    ## also installing the dependencies 'SparseArray', 'lambda.r', 'MatrixGenerics', 'S4Arrays', 'DelayedArray', 'futile.logger', 'SummarizedExperiment', 'cigarillo', 'interp', 'S4Vectors', 'Seqinfo', 'BiocParallel', 'Rsamtools', 'GenomicAlignments', 'Biobase', 'GenomicRanges', 'pwalign', 'latticeExtra', 'Rhtslib', 'Biostrings', 'reshape2', 'ShortRead', 'RcppParallel', 'IRanges', 'XVector', 'BiocGenerics'

    ## Installation paths not writeable, unable to update packages
    ##   path: /usr/local/lib/R/library
    ##   packages:
    ##     class, cluster, KernSmooth, lattice, MASS, Matrix, nlme, nnet, spatial,
    ##     survival

    ## Old packages: 'diffobj'
