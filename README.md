# Final Project

HSE 103 Data Science \|\| Fall Term 2026 \|\| Professor Meghan Muse \|\| Zoe R. Plumridge

This project is to practice data wrangling, creating visualizations in R, working on the Dartmouth high performance computers, and using git and github.

## Data Source:

https://pubmed.ncbi.nlm.nih.gov/27841759/

## References:

<https://pubmed.ncbi.nlm.nih.gov/27841759/>

R version: 4.6.1 (2026-06-24)

LaTeX version: Server Pro 6.3.2

R packages: tidyverse (ggplot2, dplyr), janitor, DataExplorer, ggtext, corrplot, ggridges, waffle, pheatmap, table1

## Data Set Information

| Variable Name | Description |
|----|----|
| subjectID | Unique subject identifier |
| geoID | Unique sample identifier |
| mat_age_yrs | Maternal age (years) |
| preg_preeclampsia | Pregnancy outcome (preeclampsia vs normal) |
| delivery_gestAge_wks | Gestational age at delivery (weeks) |
| mat_BMI | Maternal BMI (kg/m^2^) |
| mat_vitD | Maternal vitamin D (25-hydroxyvitamin D; ng/mL) at baseline |
| mat_asthma | Maternal asthma diagnosis (0 = healthy, 1 = asthma) |
| sampleCollection_gestAge_wks | Gestational age at sample collection (weeks) |
| batch_Microarray | Date/batch of RNA profiling by microarray (categorical) |

: Data Dictionary for covariate data. Provided by Meghan Muse.

The gene expression data comes from the Affymetrix Human Gene 1.0 ST Array and thus the IDs provided (i.e. row names) reflect the probe IDs from the array. 
