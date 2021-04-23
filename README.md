# SPdenovo

<!-- badges: start -->
[![R-CMD-check](https://github.com/systemPipeR/SPdenovo/actions/workflows/R_CMD.yml/badge.svg)](https://github.com/systemPipeR/SPdenovo/actions/workflows/R_CMD.yml)
[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
<!-- badges: end -->

### :construction: Under Development!

> This pipeline is currently under development and does not have a stable release yet.

### Installation

To install the package, please use the _`BiocManager::install`_ command:
```
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("systemPipeR/SPdenovo", build_vignettes=TRUE, dependencies=TRUE)
```
To obtain the *systemPipeR* and *systemPipeRdata*, please run as follow:
```
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("systemPipeR")
BiocManager::install("systemPipeRdata")
```

## Workflow environment

Workflow includes following steps:

# Trinity Transcriptome Assembly
# Assembly Quality Assessment 
## Counting Full-length Transcripts
## Contig Nx and ExN50 stats
## Examine strand-specificity of reads
# Transcript Quantification
# QC Samples and Bio Replicates
# Differential Transcript or Gene Expression
# Differential Transcript Usage
# Identifying Sequence Polymorphisms or Variants
# Coding Region Identification
# Functional Annotation of Transcripts
#  Gene Ontology term functional category enrichments