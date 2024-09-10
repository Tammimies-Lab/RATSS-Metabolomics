# Urine metabolomic profiles of autism and autistic traits – a twin study
Abishek Arora (1,2), Francesca Mastropasqua (1,2), Sven Bölte (1,3,4) and Kristiina Tammimies (1,2,*)

1. Center of Neurodevelopmental Disorders (KIND), Centre for Psychiatry Research, Department of Women's and Children's Health, Karolinska Institutet, Stockholm, Sweden
2. Astrid Lindgren Children’s Hospital, Karolinska University Hospital, Region Stockholm, Stockholm, Sweden
3. Child and Adolescent Psychiatry, Stockholm Health Care Services, Region Stockholm, Stockholm, Sweden
4. Curtin Autism Research Group, Curtin School of Allied Health, Curtin University, Perth, Western Australia

*Correspondence: [kristiina.tammimies@ki.se](mailto:kristiina.tammimies@ki.se)

**Published in *PLoS One* (2024), DOI: [10.1371/journal.pone.0308224](https://doi.org/10.1371/journal.pone.0308224) | PubMed: [39226293](https://pubmed.ncbi.nlm.nih.gov/39226293/)**

## Analysis Pipeline

Thank you for showing interest in our manuscript. In this GitHub repository you will find the source code required to replicate our analyses and figures using R. The data sets are accessible, after necessary clearances, through the Swedish National Data Service’s (SND) research data catalogue (DOI: [10.48723/6821-pn89](https://doi.org/10.48723/6821-pn89)).

### Differential Metabolomics

The the R Markdown file required for differential metabolomics analysis is included in this repository. Please refer to the methods section of the manuscript for details regarding the steps followed. In brief, differential metabolomic analysis for 208 metabolites was performed in the study cohort (N=105) using the *drgee* package in R, for overall effects and differences within twin-pairs using generalised estimating equations (GEE) models with suitable covariates.
