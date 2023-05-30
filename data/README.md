# Course data

This directory contains all the data files required to complete the course exercises.


The data disseminated from this directory consists of publicly available scRNA-seq counts derived from human CD4+ T cells. These cells are a subset of a study published in Nature Communications in 2021. Raw data can be accessed at:


Original publication: https://doi.org/10.1038/s41467-020-15543-y

Associated database:  https://www.opentargets.org/projects/effectorness


## Files
**1. matrix.mtx.gz**            Gene expression matrix containing counts for 20,953 genes in 5,269 cells. This file is in sparse Matrix (.mtx) format and was gzip compressed. 

**2. barcodes.tsv.gz**          Cell IDs corresponding to each column of the expression matrix. This file is in plain text format (.tsv) and was gzip compressed.

**3. features.tsv.gz**          Gene names corresponding to each row of the expression matrix. This file is in plain text format (.tsv) and was gzip compressed.

**4. cell-annotations.tsv.gz**  Table with annotations and metadata associated with each single cell in the expression matrix. This fils in in tab-separate value (.tsv) format and was gzip compressed.
