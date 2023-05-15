# Final_report_GWAS_1000Genomes_analysis
This repo hosts the reports generated across my final semester at Temple University for my Independent Research Capstone course done within Dr. Kulathinal's lab. The reasearch questions posed at the start of the semester which this bioinformatics analysis are centered around are: 

  1. Are there genes involved in human disease phenotypes harboring population specific SNPs?
  2. Do diseases containing population specific SNPs show significant prevalence disparities between those populations?

Read further to learn more about the analysis I performed, this README should be a helpful guide to finding all project products for those interested.

---

## Repo Navigation

The final report and supplementary materials attempt to consider the research questions and compile the entire work of the semester and project into an organized single desitnation for viewing the projects results. For further details on the process as it happened throughout the semester you can read through the Biweekly Reports section below.

The tables may also be of interest as they are some key products of the overall analysis and as such have been linked below with breif descriptions of each. 

---

### Primary Report & Supplementary Materials

  - [Final Report](https://j-t-nelson.github.io/Final_report_GWAS_1000Genomes_analysis/reports/final_report.html)
  - [Supplementary Materials](https://j-t-nelson.github.io/Final_report_GWAS_1000Genomes_analysis/reports/supplementary_mats.html)
    - *R version and packages used can be found at the bottom of the supplementary materials page*

---

### [Table](https://github.com/J-T-Nelson/Final_report_GWAS_1000Genomes_analysis/tree/main/tables_(csv)) Descriptions

[Monogenic_variants_complete.csv](https://github.com/J-T-Nelson/Final_report_GWAS_1000Genomes_analysis/blob/main/tables_(csv)/monogenic_variants_complete.csv)

  - Complete set of monogenic variants (SNPs, mutations) used wtihin this analysis. Sources of data shown in table, complete references to sources available within the Final Report linked above. 

[top_10_mono_with_fst.csv](https://github.com/J-T-Nelson/Final_report_GWAS_1000Genomes_analysis/blob/main/tables_(csv)/top_10_mono_with_fst.csv)

  - top 10 monogenic disease variants per [1000 Genomes](https://www.internationalgenome.org/) sub population according to estimated Fst ([fixation index](https://en.wikipedia.org/wiki/Fixation_index)) against the total set of populations from the 1000 Genomes study. 

[top_20_disease_with_fst.csv](https://github.com/J-T-Nelson/Final_report_GWAS_1000Genomes_analysis/blob/main/tables_(csv)/top_20_disease_with_fst.csv)

  - top 20 disease variants per [1000 Genomes](https://www.internationalgenome.org/) sub population according to estimated Fst ([fixation index](https://en.wikipedia.org/wiki/Fixation_index)) against the total set of populations from the 1000 Genomes study. 

**[CorrelationCoefficients_diseasePrevalence_vs_meanSNP_frequency.csv](https://github.com/J-T-Nelson/Final_report_GWAS_1000Genomes_analysis/blob/main/tables_(csv)/CorrelationCoefficients_diseasePrevalence_vs_meanSNP_frequency.csv)**

  - [Pearsons correlation coefficients](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient) calculated for 11 diseases (2 monogenic disease, 9 other diseases) using prevalence statistics in 11-20 sub populations of the 1000 Genomes study. Variance in number of sub populations occurrs only in Phenylketonuria and Cystic Fibrosis values as different data sources were used for their inclusion in this portion of the overall analysis.  

---

### Biweekly Reports

  1. [Report 1](https://j-t-nelson.github.io/Final_report_GWAS_1000Genomes_analysis/reports/monogenic_report_1.html)
  2. [Report 2](https://j-t-nelson.github.io/Final_report_GWAS_1000Genomes_analysis/reports/week3-4report.html)
  3. [Report 3](https://j-t-nelson.github.io/Final_report_GWAS_1000Genomes_analysis/reports/fstCalculation_dataRetrieval.html)
  4. [Report 4](https://j-t-nelson.github.io/Final_report_GWAS_1000Genomes_analysis/reports/Week7-8_report.html)
  5. [Report 5](https://j-t-nelson.github.io/Final_report_GWAS_1000Genomes_analysis/reports/week9-10report.html)
  6. [Report 6](https://github.com/J-T-Nelson/Final_report_GWAS_1000Genomes_analysis/blob/main/reports/P2G%2011-12%20report.pdf)

