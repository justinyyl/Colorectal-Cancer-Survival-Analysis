# Colorectal Cancer Survival Analysis

## Overview
This project focuses on **survival analysis** using a dataset of colorectal cancer patients. The primary objective is to evaluate factors influencing **disease-free survival (DFS)**, identify significant predictors, and assess the impact of treatments such as **radiotherapy** and **chemotherapy** on survival outcomes.

---

## Dataset Description
The dataset contains clinical information, tumor characteristics, and treatment details for colorectal cancer patients. Below are the key variables:

- **Age**: Patient's age at diagnosis (in years).
- **Dukes Stage**: Cancer progression stage (A to D).
- **Gender**: Male or Female.
- **Location**: Tumor location (Left, Right, Colon, or Rectum).
- **DFS (Disease-Free Survival)**: Time (in months) the patient remained disease-free.
- **DFS event**: Event indicator (1 = disease recurrence or death, 0 = censored).
- **Adj_Radio**: Whether the patient received radiotherapy (1 = Yes, 0 = No).
- **Adj_Chem**: Whether the patient received chemotherapy (1 = Yes, 0 = No).

---

## Objectives
1. **Explore Disease-Free Survival**:
   - Analyze how variables like **age**, **Dukes stage**, and **location** impact DFS.
   
2. **Evaluate Treatment Effects**:
   - Assess the influence of **radiotherapy** and **chemotherapy** on DFS outcomes.

3. **Model Survival Probabilities**:
   - Use **Kaplan-Meier survival curves** and **Cox proportional hazards models** to estimate survival probabilities and identify significant predictors.

---

## Results
- **Dukes Stage**:
  - Higher Dukes stages significantly increase the risk of recurrence or death, emphasizing disease severity as a major factor.
  - Patients with **Stage 0 or 1** demonstrate the best survival outcomes, with survival curves showing clear separation between stages.

- **Radiotherapy (Adj_Radio)**:
  - Radiotherapy is associated with a significant reduction in hazard, improving disease-free survival (DFS).
  - Patients receiving radiotherapy demonstrate consistently higher survival probabilities across all time points.

- **Chemotherapy (Adj_Chem)**:
  - Chemotherapy shows limited impact on DFS in this dataset, with minimal differences in survival probabilities between treated and untreated groups.

---

## Tools
- Python libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `lifelines`.
- Quarto: render `HTML`
