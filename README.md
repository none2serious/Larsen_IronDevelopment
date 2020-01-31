# Larsen_IronDevelopment

This repository contains the analysis code for "Longitudinal development of brain iron is linked to cognition in youth" (Larsen et al., 2020, DOI: https://doi.org/10.1523/JNEUROSCI.2434-19.2020).

## 1. createT2star.sh
This code snippet contains bash code to calculate T2* and R2* and spatially normalize them to the study template.

## 2. GAMM_model.Rmd
This R markdown file contains all the code for statistical anlyses and figure generation.  
The code reads in the data file brain_iron_data.Rda . 
See comments in code for more information.

## 3. Other files
All other files are used in the analysis scripts.  
* `combat.R` and `utils.R` are used for ComBat harmonization (see https://github.com/Jfortin1/ComBatHarmonization).  
* `Rainclouds.R` (for figure 3)
