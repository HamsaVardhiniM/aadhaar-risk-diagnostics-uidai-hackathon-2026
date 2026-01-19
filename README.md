# aadhaar-risk-diagnostics-uidai-hackathon-2026
This project presents a comprehensive, state-level risk diagnostics framework for the Aadhaar ecosystem, integrating enrolment inclusion risks, demographic and biometric update volatility, and PAN–Aadhaar linkage gaps. 

# Risk Diagnostics of Aadhaar  
## Inclusion Gaps, Update Volatility, and PAN–Aadhaar Linkage

### UIDAI Data Hackathon 2026  
*(Organised by UIDAI, Government of India)*

---

##  Project Overview

This repository presents a comprehensive, state-level **risk diagnostics framework** for the Aadhaar ecosystem, integrating:

- Enrolment inclusion risks  
- Demographic and biometric update volatility  
- PAN–Aadhaar linkage gaps  

The analysis moves beyond aggregate counts to uncover **structural, behavioural, and operational drivers** of exclusion and data staleness.  
The findings enable **targeted, feasible, and policy-relevant interventions** aligned with UIDAI’s mandate of delivering an **inclusive, reliable, and up-to-date digital identity ecosystem**.

---

##  Submission Context

This project was developed and submitted as part of the **UIDAI Data Hackathon 2026**.

 **Submission Date:** January 2026  

---

##  Tools Used

- **Python**
- **Pandas, NumPy** — data cleaning, aggregation, statistical analysis  
- **Matplotlib, Seaborn** — trend and risk visualisation  
- **GeoPandas** — state-level geospatial risk mapping  
- **Jupyter Notebooks** — reproducible analysis workflows  
- **GitHub** — version control and project hosting  

---

## 📁 Repository Structure

The repository is organised into **three problem statement–specific folders**, each following a consistent and reproducible structure.
```
aadhaar-risk-diagnostics-uidai-hackathon-2026/
│
├── Enrolments-inclusion-risk-analysis/
├── Updates-risk&trend-analysis/
└── PAN_Aadhar_Linkage_Risk-analysis/  
```

Each problem statement folder contains the following subfolders:

- **raw/** — Original datasets used for analysis  
- **intermediate/** — Cleaned or aggregated datasets generated during preprocessing  
- **notebooks/** — Jupyter notebooks and methodology documents covering the full analytical workflow  
- **final/** — Final datasets and visual outputs used for insights and reporting  

---

## 1️⃣ Enrolments-inclusion-risk-analysis

### Purpose
Assessment of enrolment coverage gaps by comparing Aadhaar enrolments against projected population estimates to identify **inclusion risk hotspots**.

### Folder Details
```
Enrolments-inclusion-risk-analysis/
│
├── raw/
│ ├── census_data_2011.xls
│ ├── enrolments_2025_df.csv
│ └── statewise_growthrate.csv
│
├── intermediate/
│ ├── census_2011_aggregated.csv
│ └── census_data_2011_cleaned.csv
│
├── notebooks/
│ ├── 01_enrolment_aggregation.ipynb
│ ├── 02_census_aggregartion.ipynb
│ ├── 03_census_2025_projection.ipynb
│ ├── 04_inclusion_risk_analysis.ipynb
│ └── Methodology_2025_population_estimation.docx
│
├── final/
│ ├── enrolments_2025_statewise.csv
│ ├── population_estimation_2025.csv
│ ├── Inclusion_Risk_Index_cohortwise.png
│ ├── risk_high_enrolment_5_17.png
│ ├── risk_high_enrolment_18_plus.png
│ ├── risk_low_enrolment_0_5.png
│ └── top10_inclusion_risk_index.png

```
---

## 2️⃣ Updates-risk&trend-analysis

### Purpose
Analysis of **biometric and demographic update behaviour** to identify volatility patterns, reactive updates, and campaign-linked surges.

### Folder Details
```
Updates-risk&trend-analysis/
│
├── raw/
│ ├── biometric_updates_2025_df.csv
│ ├── demographic_updates_2025_df.csv
│ └── population_estimation_2025.csv
│
├── intermediate/
│ ├── statewise_demo_updates_monthly_aggregated.csv
│ ├── statewise_bio_updates_monthly_aggregated.csv
│ └── cohort_5_17_bio_updates_aggregated.csv
│ 
│
├── notebooks/
│ ├── 01_updates_aggregation.ipynb
│ └── 02_updates_risks_trends_analysis.ipynb
│
├── final/
│ ├── biometric_statewise_trends_2025.png
│ ├── demographic_statewise_trends_2025.png
│ ├── biometric_update_intensity_5_17_barplot.png
│ ├── biometric_update_intensity_5_17_table.png
│ ├── biometric_volatility_risk_2025.png
│ └── demographic_volatility_risk_2025.png
```



---

## 3️⃣ PAN_Aadhar_Linkage_Risk-analysis

### Purpose
A two-part diagnostic analysis to quantify **PAN–Aadhaar linkage risk (PALRI)** and investigate the underlying drivers using inclusion and update-risk overlays.

### Folder Details
```
PAN_Aadhar_Linkage_Risk-analysis/
│
├── raw/
│ ├── Part1_analysis/
│ │ ├── Aadhar-Saturation2025.csv
│ │ ├── PAN_linked_as_on2023.csv
│ │ └── population_estimation_2025.csv
│ │
│ ├── Part2_analysis/
│ │ ├── biometric_volatility_risk.csv
│ │ ├── demographic_volatility_risk.csv
│ │ └── inclusion_risk_ranking.csv
│ │
│ └── States_Mapping_Shapefiles/
│ └── (Indian state shapefiles for geomapping)
│
├── notebooks/
│ └── 01_PAN_Aadhar_Linkage_Risk-analysis.ipynb
│
├── final/
│ ├── PALRI_India_Risk_Map.png
│ └── PALRI_Risk_Table.png

```
---

##  Reproducibility Notes

- All analyses are fully reproducible using the provided Jupyter notebooks.
- Python libraries used are standard data science packages commonly available in Anaconda environments.

---

##  Usage & Citation

- This repository has been created exclusively for academic analysis, research and analytics demonstration, and evaluation under the UIDAI Data Hackathon 2026.

- The contents of this repository — including datasets, analytical methods, notebooks, visualisations, and derived insights — must not be reused, reproduced, or submitted as part of any other competition, hackathon, or evaluative process.

---

##  Author

**Hamsa Vardhini M**  
B.Tech — Artificial Intelligence and Data Science  
St. Joseph’s College of Engineering, Chennai  

---

## 🔗 GitHub Repository

[github.com/HamsaVardhiniM/aadhaar-risk-diagnostics-uidai-hackathon-2026]



