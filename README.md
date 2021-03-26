# GWAS-with-python
This is a little example on how python can be useful to analyse molecular markers such as SNPs.

The aim of this work is to find possible association among markers and phenotype, using a dataset based on human sample picked from more than one million individuals. In this little project I am going to analyse to the phenotype ‘automobile speeding propensity’ (the tendency to drive faster than the speed limit) and its assosiation with molecular markers.

The analysis will be highlighting the markers with lowest p-value and therefore, the most significative in terms of association with risk-related phenotype; in this regard, I am going to transform p-values in their negative logarithm to make the plot more readable. The negative log of p-value will be in y-axis and the chromosome number in the x-axis.

The data was taken from the database (https://www.thessgac.org/data) related to the study: https://www.nature.com/articles/s41588-018-0309-3.

General information about this study:

-population were sample-size-weighted from meta-analysis of ten smaller cohorts from seven studies.

-SNPs genotyping was performed by using a range of commercially available genotyping arrays; ~11,515,000 SNPS were analyzed.
