# Survival Analysis of Colorectal Cancer Patients

## Description
This project focuses on survival analysis using a colorectal cancer patient dataset. The primary objective is to evaluate factors affecting disease-free survival (DFS) in patients who have undergone tumor removal surgery. By leveraging survival analysis techniques, the project aims to provide insights into the progression and recurrence of the disease, as well as the impact of treatments like radiotherapy and chemotherapy on patient outcomes.

---

## Dataset Description
The dataset contains clinical information about colorectal cancer patients, including demographics, tumor characteristics, and treatment details. Below is the list of variables:

- **Age**: Patient's age at diagnosis (in years).
- **Dukes Stage**: Cancer progression stage (A to D).
- **Gender**: Male or Female.
- **Location**: Tumor location (Left, Right, Colon, or Rectum).
- **DFS (Disease-Free Survival)**: Time (in months) the patient remained disease-free.
- **DFS event**: Event indicator (1 = disease recurrence or death, 0 = censored).
- **Adj_Radio**: Whether the patient received radiotherapy (1 = Yes, 0 = No).
- **Adj_Chem**: Whether the patient received chemotherapy (1 = Yes, 0 = No).
