# BNrich-RData
The RDtata for starting  BNrich package

Hi dear users

These are the start files for BNrich package include 187 preprocessed KEGG pathways 
which their cycles were removed (a list named mapkG), the data frame includes information about the pathways
(a data.frame named PathName_final) and the vector of pathways IDs (a character vector named pathway.id).
# BNrich
The R package for pathway enrichment analysis based on Bayesian Network. For documentation, please visit [the vignette](https://github.com/Samaneh-Bioinformatics/BNrich/blob/master/vignettes/BNrich-vignette.pdf).

### Install instructions

Dependencies are listed in `DESCRIPTION`

**Installing from source**

You can point your R's `install.packages` function at [BNrich_0.1.0.tar.gz](https://github.com/Samaneh-Bioinformatics/BNrich/raw/master/BNrich_0.1.0.tar.gz). Consider that the version of R must be at least 3.6.1. Open an R terminal and execute the following:

	install.packages("BNrich_0.1.0.tar.gz", type="source", repos=NULL)
	library("BNrich")


You can also source individual files as needed instead of installing the entire package.

	# For example
	source("BNrich/R/BNrich.R")
