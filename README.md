# Length-of-Stay-Prediction-for-Heart-Disease-Patients
## Introduction
This project utilizes the CMS DE-SynPUF dataset (2008–2010) to analyze healthcare patterns of heart disease patients by linking beneficiary, inpatient, outpatient, and prescription files. Focusing on a 5% sample of Medicare beneficiaries, the aim is to explore factors affecting hospital length of stay (LOS). The analysis emphasizes the impact of comorbidities, medication use, and healthcare services, using exploratory data analysis (EDA) to uncover trends and inform predictive modeling.

## Data Preparation
The data preparation process involved merging 15 samples from various Medicare files into a master dataset, filtering for patients diagnosed with heart disease using ICD-9 codes, in total of more than 10 million rows. Feature engineering included calculating age, LOS, and a new variable for prior six-month payments. Prescription data was cleaned, aggregated by year, and merged based on patient IDs. Outpatient data was selectively integrated based on physician involvement. 

## Exploratory Data Analysis (EDA)
EDA revealed that median LOS remained stable at around five days across years, with outliers indicating some prolonged stays. Most first diagnoses fell under the “Other” category, though heart disease subtypes were consistently present. Females and older adults (65–85) were more affected by chronic diseases. Drug utilization and financial burdens varied by disease type, with Heart Failure and COPD showing higher prescription and payment levels. Physician involvement also appeared to influence LOS, and cost distributions remained steady but showed disease-specific variations.
