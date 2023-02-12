# GTEx_SmokerStatus - smoking data
Exploratory Analysis of changes in gene expression in the Lung based on transcripts per million and covariates data obtained from GTEx Portal.

## About
Smoking is known to cause mutations, but recent studies suggested that smoking can cause a change in gene expression for a multitude of genes across tissues, including Lung. 
Smoking also, thus acts a huge confounder in many lung-cancer related studies and research involving Gene expression, and for those utilizing GTEx gene expression data. As the smoking status is not specified. 
Studies have shown that Smoking highly changes the expression of genes like CYP1B1 which play an important role in metabolic activation of pro-carcinogens. Over expression of these genes have shown to be linked with cancer progression in the Lung. 
These changes in gene expression are irreversible and can act as markers for smoking in individuals. Thus, the aim of the project was to utilize these biomarkers and build a model which can cluster inviduals as smokers or non-smokers utilizing the gene expression data from GTEx. 
It would help elimiate smoking as a biological confounder in studies related to Lung-cancer utlizing data from GTEx. As smoking status of the inividual could be charecterised. 

Contains the code for :

1. Creation of two clusters - Based on gene expression TPM data as well as Covariates data and the comparison of the clusters in each data-set

2. Plots and analysis of the two clusters 

Contains the results:

1. Cluster plots for the clusters created based on all covariates data, as well as only the most correlated data

2. Cluster comparison matrices on basis of various comparison metrics
