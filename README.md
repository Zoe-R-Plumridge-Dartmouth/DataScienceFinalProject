# Final Project

HSE 103 Data Science \|\| Fall Term 2026 \|\| Professor Meghan Muse \|\| Zoe R. Plumridge

This project is to practice data wrangling, creating visualizations in R, working on the Dartmouth high performance computers, and using git and github.

## Data Source:

https://pubmed.ncbi.nlm.nih.gov/27841759/

## References:

<https://pubmed.ncbi.nlm.nih.gov/27841759/>

R version:

LaTeX version:

HPC Used:

R packages

## Assignment Guidelines:

### Part 1 

Due 10/21 3 pm

Submit: 1) a single knitted PDF file and (2) your corresponding R markdown file.

From the provided data, identify one gene, one continuous covariate, and two categorical covariates of interest. [At least one]{.underline} categorical variable should be derived from a continuous variable. All submitted plots must be made using *ggplot2* and must be of [publication quality]{.underline}.

### Part 2 

Due

Identify 2 additional genes from the above data (3 total). For this submission, you will build a function that produces the plots for submission 1 above. [Your plots should also incorporate any feedback from Submission 1.]{.underline}

Your function should take the following inputs:

1.         Data frame

2.         List of 1 or more gene names

3.         Name of continuous covariate (1)

4.         Name of categorical covariates (2)

### GitHub Component

Create a private repository on GitHub for this project prior to Submission 1. You must have a commit from *before* each submission including all of the code used for each submission (**5pts/submission; 15 pts total**).

The repository must be made public on the due date for the final submission. All points for GitHub submission will go towards your final submission grade. You can receive **up to 3 bonus points** towards the final submission by having an additional push *prior* to each submission (**1 pt available per submission**). To be eligible for a bonus point, additional pushes must occur on a separate day and the changes between pushes must be substantial (i.e. don’t just change one line of code. \

### Final Submission 

Due last week of class

Your final project should be submitted as a formatted LaTeX document with the following sections:

[Methods]{.underline}

·       Describe and cite the data source including initial sample size

·       Final sample size and justification for removing any data points (if applicable)

·       Describe any analyses conducted

·       Cite software and packages (and versions used)

·       Link GitHub repository

[Results]{.underline}

·       Description of the findings of each table/figure (outlined below). For each item, provide a brief statement referencing and interpreting them and then cite the relevant table or figure, as discussed in class. Example: “Gene x was not associated with covariate y (Figure 2).” All items must be typeset with captions/figure legends as discussed in class.

·       Summary statistics table (LaTeX formatted) with all covariates you looked at and 2 additional continuous covariates (3 continuous, 2 categorical total), stratified a categorical covariate

·       Publication quality plots from submission 1 (incorporating any previous feedback)

·       Publication quality heatmap (10 genes, tracking bars for 2 categorical variables, clustering)

·       One additional plot type not previously discussed in class to visualize your data in a new and unique way. Be creative! See list at end of document for plot types that would not count.

[References]{.underline}

At a minimum, your references must include the original paper that the dataset came from and any R packages used. All references should be cited within the text as shown in class.

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

To match the covariate data (GSE85307_covar.csv) to the gene expression data (GSE85307_geneExpression.csv), you should use the geoID provided in the covariate file and the column names in the gene expression file. Make sure you verify that you are correctly matching the gene expression data to the appropriate covariate data.

The gene expression data comes from the Affymetrix Human Gene 1.0 ST Array and thus the IDs provided (i.e. row names) reflect the probe IDs from the array. I have already created a linker file for you (GSE85307_geneNames.csv) so that you can match the relevant probe IDs to the appropriate gene name.
