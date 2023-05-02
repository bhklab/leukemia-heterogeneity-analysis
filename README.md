# Heterogeneity in leukemia cells that escape drug-induced senescence-like state

Senescence gene signatures are considered and their association with overall survival in AML are assessed. 

## Data

- BCLQ-Leucegene cohort including GSE49642, GSE52656, GSE62190, GSE66917, GSE67039. 

- BeatAML cohort

## Signature Analysis

For the signature analysis, the log2 transformed of transcript per million (TPM) RNA-seq expression data is considered for the analysis. The signature score is computed using mean approach. The Cox regression model is considered to assess the association of signatures with survival outcome (OS) per cohort. Kaplan-Meir (KM) survival curves were plotted for groups of patients for the binary signatures based on quartile or median cut-offs. A log-rank test was performed to determine the p-value. Multiple test correction approach; Benjamini & Hochberg; is applied to control the false discovery rate (FDR).

