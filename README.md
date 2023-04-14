# Maven_at_al_2023_SrivastavaLab

## Introduction

This repository contains the code used by Dr. Bonnie EJ Maven with assistance and insight from Dr. Casey Gifford, Mr. Angelo Pelonero and Dr. Tomohiro Nishino in the Srivastava Lab for the submission of "The multi-lineage transcription factor ISL1 controls cardiomyocyte cell fate through interaction with NKX2.5."

Manuscript link will be posted here when available.

## Analysis
The data processing and analysis were carried out using Cellranger, Seurat, and supporting packages, as detailed in the provided scripts.

### Day 8 Cardiac Progeinitors (CPs) Data Analysis Overview

1. Process scRNA with 10x Genomics Cellranger pipelines:
   - `cellranger count`
   - `cellranger aggr`

2. Analyze scRNA seq data with Seurat using cp scripts 1-6 found in the `day8_cp/*/` folder:
- `cp_1_preprocessing.Rmd`: Data import, QC filtering, and clustering.
- `cp_2_processing.Rmd`: Data subsetting into objects used in the subsequent four analysis scripts.
- `cp_3_WT_IKO_analysis.Rmd`: Analysis of WT and ISL1 KO subsets.
- `cp_4_WT_analysis.Rmd`: Analysis of WT subset.
- `cp_5_siRNA_analysis.Rmd`: Analysis of siRNA conditions subsets.
- `cp_6_WT_KOs_analysis.Rmd`: Analysis of WT, ISL1 KO, and NKX2.5 KO subsets.

## Data Availability

All sequencing data will be made available through GEO/SRA upon the publication of the manuscript.
