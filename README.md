# Classifying COVID-19 Based on the Temporal Sequence of Symptoms

## Overview

This project investigates the progression and classification of COVID-19 cases based on the temporal order of symptom onset. The goal is to derive structured patterns from patient-reported symptoms to inform the development of early detection tools and clinical decision support systems. The analysis leverages real-world data and applies a combination of descriptive statistics, temporal sequence analysis, and classification logic to uncover common symptom trajectories.

## Type of Analysis

**Descriptive Analysis**  
- Frequency distribution of individual symptoms, vaccination status, and testing modalities.  
- Summary of demographic variables including age and gender.

**Temporal Sequence Analysis**  
- Pairwise comparison of symptom onset timing to determine likely progression patterns.  
- Symptom ordering is assessed using structured patient input and sequence logic.

**Rule-Based Classification**  
- Patients are grouped based on the dominant sequence of symptoms.  
- Differences in symptom order are quantified and tabulated to establish common trajectories.  
- Classification is guided by domain knowledge and structured logic, rather than predictive modeling.

---

## Research Objectives

- Describe the frequency and co-occurrence of COVID-19 symptoms.  
- Determine the typical sequence in which symptoms appear among COVID-19 patients.  
- Identify consistent symptom orderings that can aid in early detection and classification.  
- Provide structured evidence to support symptom-based triage strategies in healthcare settings.

---

## Data Description

The dataset contains structured clinical and survey variables, including:

- **Demographic Information**: Age, Gender  
- **Vaccination Status**: Dose completion, date of last dose  
- **Testing Information**: Home test results, PCR lab test results  
- **Symptom Data**: Binary variables indicating presence and timing of symptoms such as:  
  - Fatigue  
  - Shortness of breath  
  - Fever  
  - Cough  
  - Loss of taste/smell  
  - Headache  
  - Sore throat  

---

## Methodology

1. **Data Cleaning**  
   - Replaced missing values with structured placeholders  
   - Binarized categorical variables such as gender and test result  

2. **Symptom Extraction**  
   - Selected relevant symptom columns and created a clean symptom matrix  
   - Grouped symptoms into co-occurring and non-co-occurring sets  

3. **Temporal Analysis**  
   - Counted how often one symptom appeared before another  
   - Constructed pairwise comparisons using symptom timing fields  
   - Aggregated results into a temporal ordering matrix  

4. **Classification**  
   - Defined dominant symptom sequences  
   - Grouped patients into classes based on these sequences  
   - Quantified differences using patient counts per group  

---

## Tools & Technologies

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Logical rule-based sequence modeling

---

## Key Contributions

- Identified consistent and clinically meaningful sequences of COVID-19 symptoms  
- Developed a rule-based classification framework rooted in real-world symptom progression  
- Provided a structured data model that can inform triage logic and public health response

---

## Author

**Alanoud Alturki**  
Health Data Analyst | Health Informatics Specialist | Pharmacist  
[LinkedIn](https://www.linkedin.com/in/alanoud-alturki-5601b2b5)

---

## License

This project is provided for academic, research, and non-commercial use.  
All data has been anonymized and processed in accordance with ethical standards.
