# systemPipeDeNovo <img src="https://github.com/tgirke/systemPipeR/raw/gh-pages/images/systemPipeR.png" align="right" height="139" />

<!-- badges: start -->

[![platforms](http://www.bioconductor.org/shields/availability/3.10/systemPipeR.svg)](http://www.bioconductor.org/packages/devel/bioc/html/systemPipeR.html#archives)
[![rank](http://www.bioconductor.org/shields/downloads/devel/systemPipeR.svg)](http://bioconductor.org/packages/stats/bioc/systemPipeR/)
[![posts](http://www.bioconductor.org/shields/posts/systemPipeR.svg)](https://support.bioconductor.org/t/systempiper/)
[![Bioc](http://www.bioconductor.org/shields/years-in-bioc/systemPipeR.svg)](http://www.bioconductor.org/packages/devel/bioc/html/systemPipeR.html#since)
[![build](http://www.bioconductor.org/shields/build/devel/bioc/systemPipeR.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/systemPipeR/)
[![updated](http://www.bioconductor.org/shields/lastcommit/devel/bioc/systemPipeR.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/systemPipeR/)
[![dependencies](http://www.bioconductor.org/shields/dependencies/devel/systemPipeR.svg)](http://www.bioconductor.org/packages/devel/bioc/html/systemPipeR.html#since)
![R-CMD-check](https://github.com/systemPipeR/systemPipeDeNovo/workflows/R-CMD-check/badge.svg)
<!-- badges: end -->

> This pipeline is currently under development and does not have yet stable release.

## Introduction

#### Installation 
To install the package, please use the _`BiocManager::install`_ command:
```
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("systemPipeR/systemPipeDeNovo", build_vignettes=TRUE, dependencies=TRUE)
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

1. Read preprocessing
    + Quality filtering (trimming)
    + FASTQ quality report
2. Trinity Transcriptome Assembly
3. Assembly Quality Assessment 
4. Transcript Quantification
5. QC Samples and Bio Replicates
6. Differential Transcript or Gene Expression
7. Differential Transcript Usage
8. Identifying Sequence Polymorphisms or Variants
9. Coding Region Identification
10. Functional Annotation of Transcripts
11. Gene Ontology term functional category enrichments