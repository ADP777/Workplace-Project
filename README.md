# Workplace-Project
ExploreAI individual project
# Workplace-Project – Insurance Claims Fraud Detection

CapStone Individual Project for the QCTO Workplace Module (ExploreAI).

This repository contains an end-to-end data science workflow for detecting potential
fraudulent insurance claims, using the `insurance_claims` dataset provided as part of
the Workplace Module.

## 1. Project Overview

The African insurance industry has a relatively small share of global insured catastrophe
losses despite being home to a large share of the world’s population. This project explores
an insurance claims dataset to:

- Understand patterns in claims and fraud behaviour.
- Build a supervised machine learning model to predict whether a claim is fraudulent.
- Demonstrate a full data science workflow: data collection, cleaning, EDA, modelling,
  evaluation, and reporting.

## 2. Dataset

- **Source:** `insurance_claims_raw.xlsx` from the ExploreAI Public-Data GitHub repository.
- **Working file:** `insurance_claims.csv` (cleaned and exported from Excel).
- **Target variable:** `fraud_reported`  
  - `Y` – fraudulent claim  
  - `N` – legitimate claim
- **Key feature groups:**
  - Policy and premium information
  - Insured demographics (occupation, education, relationship)
  - Vehicle details (make, model, year)
  - Incident details (type, severity, state, hour of day)
  - Claim amounts (injury, property, vehicle, total)

The data was manually cleaned in Excel (removing empty columns, fixing formats) and then
further processed in the notebook (date parsing, handling missing values, dropping ID-like
columns).

## 3. Repository Structure

- `QCTO---Workplace-Module-Notebook-Template-4571.ipynb`  
  Main analysis notebook containing:
  1. Importing Packages  
  2. Data Collection and Description  
  3. Loading Data  
  4. Data Cleaning and Filtering  
  5. Exploratory Data Analysis (EDA)  
  6. Modeling  
  7. Evaluation and Validation  
  8. Final Model  
  9. Conclusion and Future Work  
  10. References  

- `insurance_claims.csv` – cleaned dataset used in the notebook.  
- `README.md` – project description and usage instructions.  
- (Optional) `Capstone_Insurance_Fraud_Project_Summary.pptx` – slide deck summarising the project.

## 4. Environment and Requirements

This project was developed in Python using Jupyter Notebook.

Core dependencies:

- `python` (3.9+ recommended)
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

You can install packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
