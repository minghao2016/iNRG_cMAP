---
layout: page
title: Installation
---


## Source code and supplementary data 

**Supplementary Dataset DS1: cMap Drugs prototype ranked lists**  

Compressed tab delimited txt file containing the 'prototype ranked lists' of genes for all the drug contained in the connectivity map dataset, computed as described in [Iorio et al, PNAS 2010](http://www.ncbi.nlm.nih.gov/pubmed/20679242).  
[SuppDataset_SD1_DRUG_PRLS_txt.zip](home_files/SuppDataset_SD1_DRUG_PRLS_txt.zip "home_files/SuppDataset_SD1_DRUG_PRLS_txt.zip")  

## How to reproduce results and figures presented in the manuscript?  

### To start:  

- Make sure you have R installed. You can download it from [here](http://cran.ma.imperial.ac.uk/)
- We strongly recommend to install and use the RStudio interface to R, downloadable from [here](http://www.rstudio.com)

### Required libraries:  

Make sure you have the following libraries installed (all available on the [CRAN](http://cran.r-project.org/ "http://cran.r-project.org/") repository):  

- [mixtools](http://cran.r-project.org/web/packages/mixtools/index.html "http://cran.r-project.org/web/packages/mixtools/index.html")  

- [sROC](http://cran.r-project.org/web/packages/sROC/index.html "http://cran.r-project.org/web/packages/sROC/index.html")  

- [pheatmap](http://cran.r-project.org/web/packages/pheatmap/index.html "http://cran.r-project.org/web/packages/pheatmap/index.html")  

- [beeswarm](http://cran.r-project.org/web/packages/beeswarm/index.html "http://cran.r-project.org/web/packages/beeswarm/index.html")

To install them use the following command from the RStudio console:  

```{R}
install.packages(“[library.name]”)  
```

replacing \[`library.name`\] with each of the library names listed above, in turn.  

### Working directory creation:  
Download and unzip the following compressed folder: [IorioEtAl_R_code_and_objects.zip](home_files/IorioEtAl_R_code_and_objects.zip "home_files/IorioEtAl_R_code_and_objects.zip")

Once uncompressed, the content of this folder and its sub-folders should not be changed. Files in the OUTPUT subfolder (initially empty) can be moved and/or deleted.

### Working directory setup:  

To set the working directory to IorioEtAl_R_code_and_objects use the following command from the RStudio console:  

```{R}
setwd(‘[path]/IorioEtAl_R_code_and_objects’)  
```

replacing `[path]` with the path of the _IorioEtAl_R_code_and_objects_ directory.  

**Ready to go!**

To reproduce results and figure presented in our manuscript execute the commands contained in the following pipelines:  

[Network guided iterative connectivity mapping pipeline](http://www.ebi.ac.uk/~iorio/PLoS_ONE_Submission/iterativeCmappingPL/IterativeCmappingPipeline.html)  

[Pipeline for predictive ability validation through the signature reversion paradigm](http://www.ebi.ac.uk/~iorio/PLoS_ONE_Submission/sigRevPL/SigRevPL.html)  

### References:  

[1] Lamb J. The Connectivity Map: a new tool for biomedical research. _Nature Reviews Cancer_. 2007;7(1): 54–60\.  

[2] Iorio F, Bosotti R, Scacheri E, Belcastro V, Mithbaokar P, Ferriero R, et al. Discovery of drug mode of action and drug repositioning from transcriptional responses. _Proceedings of the National Academy of Sciences_. 2010;107(33):14621.  

[3] Iorio F, Rittman T, Ge H, Menden M, Saez-Rodriguez J. Transcriptional data: a new gateway to drug repositioning? _Drug Discovery Today. Elsevier Ltd;_ 2013 Apr 1;18(7-8):350–7.  

[4] Garnett MJ, Edelman EJ, Heidorn SJ, Greenman CD, Dastur A, Lau KW, et al. Systematic identification of genomic markers of drug sensitivity in cancer cells. _Nature. Nature Publishing Group;_ 2012 Mar 20;483(7391):570–5.
