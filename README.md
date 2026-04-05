# Evaluating AI/ML Credit Risk Models in U.S. Mortgage Lending
A Multi-Dimensional Model Risk Scoring Framework (MRRS)

Walsh College | QM640 Data Analytics Capstone | Winter 2025
Mentor: Keya Choudhury Ganguli

## Overview
This repository contains all code, data samples, and documentation 
for the capstone project evaluating AI/ML credit risk models across 
four SR 11-7 dimensions: predictive performance, fairness, 
explainability, and stability/drift.

## Data Sources
- HMDA 2024: https://ffiec.cfpb.gov/data-publication/snapshot-national-loan-level-dataset
- Fannie Mae: https://capitalmarkets.fanniemae.com/credit-risk-transfer/single-family-credit-risk-transfer/fannie-mae-single-family-loan-performance-data
- FHFA PUDB: https://www.fhfa.gov/data/pudb

## Repository Structure
capstone/
├── data/
│   ├── hmda_2024_sample.csv
│   ├── fanniemae_performance_panel.csv
│   └── fhfa_pudb_supplement.csv
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_rq1_model_training.ipynb
│   ├── 03_rq2_fairness_analysis.ipynb (access: DIR, Equalized Odds; pricing: OLS regression)
│   ├── 04_rq3_shap_explainability.ipynb
│   ├── 05_rq4_psi_drift.ipynb
│   └── 06_rq5_mrrs_scoring_tool.ipynb
└── reports/  (synopsis.pdf, final_report.pdf)
All notebooks include markdown documentation and retained output cells for full reproducibility. No proprietary or personally identifiable data is stored in the repository.
