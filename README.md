# Cyto-Feature Engineering Manuscript

This repository contains the code to analyze the data and create the plots for the manuscript, "Cyto-Feature Engineering: A Pipeline for Flow Cytometry Analysis to Uncover Immune Populations and Association with Disease". [May want to add info about how this code can be reused and / or a license / copyright info.]

This repository contains data from two projects: The first project (Project 1) contains lung data from C57BL/6 mice that were vaccinated with either BCG or PBS (control). The mice were subsequently infected with *Mycobacterium tuberuclosis* and evaluated 30, 60, and 90 days post-infection. The second project (Project 2) contains human whole blood data from a healthy individual.

Repository Directory

- CFU.Rmd : code to plot and calculate significant differences between bacterial burden for Project 1
- BCG_v_PBS.Rmd : analysis pipeline for Project 1
- Human_clinical.Rmd : analysis pipeline for Project 2
- Lineage_Table.Rmd : code to create the tables to describe the lineage and cell phenotype in Project 1
- Time_BCG_v_PBS.Rmd : code to calculate the amount of time it takes to execute analysis pipeline on Project 1 for different inputs of cells

Note: The .fcs files are too large to push to Github. The data can be obtained from Amy Fox (amyfox@colostate.edu). The data is also published on FlowRepository https://flowrepository.org/id/RvFrMfWyY0wR3ZM3cvlsAsQPBmAOXmMUzURGm1D8V0ShqSNnH2UCrPdpttuoqNS4. 
