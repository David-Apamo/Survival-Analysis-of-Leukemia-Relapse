# Survival-Analysis-of-Leukemia-Relapse
This repository contains project files for Survival Analysis of Leukemia Relapse. The study uses the Leukemia Remission dataset, which is one of the cancer-related datasets found in the **OncoDataSets** R package. The study aims to investigate the effectiveness of maintenance therapy (using antileukemic compound 6-mercaptopurine) on Leukemia remission, and how covariates like sex and white blood cell count impact survival.

## Models Used
* Kaplan Meier Model
* Cox Proportional Hazard Model

## Results
KM results: The 6-MP treatment was effective (p < .05). Patients who were under the maintenance therapy had higher survival rates. The median survival time for patients who received the 6-MP treatment was 23 weeks, while that of patients who received placebo was 9 weeks.

Results from Cox PH model show that;

* Holding the WBC covariate constant, the risk of Leukemia relapse for patients who received 6-MP treatment is reduced by a factor of 0.25, or 74.99%.
* Every unit increase in WBC count induces the hazard of Leukemia relapse by a factor of 5.42 (Increased accumulation of abnormal cells in the bone marrow and the blood crowds out healthy cells, thereby increasing the hazard of Leukemia relapse).

## Tools and Libraries
Rstudio (OncoDataSets, tidyverse, survival, survivalAnalysis, survminer)
