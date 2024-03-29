# CancerStemID
---
title: "An Introduction to the CancerStemID R-package"
author:
- name: "Andrew E. Teschendorff"
  affiliation: 
  - CAS Key Lab of Computational Biology, PICB, SINH
  - UCL Cancer Institute, University College London
date: "2021-4-25"
package: CancerStemID
output:
  BiocStyle::html_document:
    toc_float: true
---
  


# Summary

The purpose of the `CancerStemID` R-package is to illustrate the functionality of a number of R-functions for estimating various measures of cancer-risk from a single-cell RNA-Seq dataset that has profiled cells from all major stages of cancer development including normal, preneoplastic and cancer cells. Specifically, it aims to identify the cells at highest risk of neoplastic transformation.

# Installation

To install:

```r
library(devtools)
devtools::install_github("aet21/CancerStemID")
```


# References
 
Liu T, Zhao X, Lin Y, Luo Q, Zhang S, Xi Y, Chen Y, Lin L, Fan W, Yang J, Ma Y, Maity AK, Huang Y, Wang J, Chang J, Lin D, Teschendorff AE, Wu C. Computational Identification of Preneoplastic Cells Displaying High Stemness and Risk of Cancer Progression. Cancer Res. 2022 Jul 18;82(14):2520-2537. doi: 10.1158/0008-5472.CAN-22-0668. 

Teschendorff AE, Enver T.  Single-cell entropy for accurate estimation of differentiation potency from a cell's transcriptome. Nat Commun. 2017 Jun 1;8:15599. doi: 10.1038/ncomms15599

Teschendorff AE, Wang N. Improved detection of tumor suppressor events in single-cell RNA-Seq data. NPJ Genom Med. 2020 Oct 7;5:43. doi: 10.1038/s41525-020-00151-y

Yao J et al. Single-cell transcriptomic analysis in a mouse model deciphers cell transition states in the multistep development of esophageal cancer. Nat Commun. 2020 Jul 24;11(1):3715. doi: 10.1038/s41467-020-17492-y.
