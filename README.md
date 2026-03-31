# RSPARROW Model – Southeast TN

## Overview
This repository contains scripts and input datasets for running a Regional SPARROW (RSPARROW) model to estimate Total Nitrogen (TN) loads across the Southeastern United States.

The SPARROW framework estimates mean annual nutrient loads using watershed source inputs, land-to-water delivery variables, and in-stream attenuation processes.

---

## Repository Structure

### Model Scripts
- `sparrow_control.R`
- `SE_TN_sparrow_control.R`  
  Main scripts used to run the model

- `userModifyData.R`
- `SE_TN_userModifyData.R`  
  Data preprocessing and modification

---

### Input Data
- `parameters.csv`, `SE_TN_parameters.csv`  
  Model parameters

- `design_matrix.csv`, `SE_TN_design_matrix.csv`  
  Predictor variables

- `dataDictionary.csv`, `master_dataDictionary.csv`  
  Metadata

- `SE_TN_userSettings.csv`  
  User-defined settings

---

## Requirements

Run in R / RStudio.

Install required packages:

```r
install.packages(c("tidyverse", "data.table"))
