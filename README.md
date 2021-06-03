# Evaluation of Somatic Mutations in Solid Metastatic Pan-Cancer Patients

 This repository contains the data and codes used for the manuscript titled "Evaluation of Somatic Mutations in Solid Metastatic 
Pan-Cancer Patients." 

# Datasets

You will need to load the `coh_fm.rda` to run the codes.
    `simp_fm` contains simplified dataset for creating mutation frequencies for Figure 1
    `clinicalData` contains cleaned up clinical data of our metastatic cohort
    `coh_umich` contains top mutated genes from the City of Hope 2020 and University of Michigan 2017 metastatic datasets for comparison
    `fm_model` contains cleaned dataset for mutual exclusivity and co-ocuurence analysis
    `all_surv_merged` contains all clinical and mutational data 
    `No.drugs`, `No.patients` and `drug_heatmap` contain cleaned up data for treatment analysis
    
# Required R packages

    ggplot2
    survival
    survmier
    dplyr
    ggplot2
    gridExtra
    ComplexHeatmap
    GenVisR
    stringr
    discover
    ALL
    Hmisc
