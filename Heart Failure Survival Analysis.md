# Heart Failure Survival Analysis Dashboard

## Overview

This dashboard provides a comprehensive analysis of survival rates among patients with heart failure based on various factors such as age, gender, medical conditions, and laboratory results. The visualizations highlight relationships between survival status and patient attributes.

---

## Key Insights

### Summary Metrics:
- **Average Age**: 60.83 years  
- **Total Male Patients**: 194  
- **Total Female Patients**: 105  
- **Total Individuals**: 299  
- **Total Deaths**: 96  

### Donut Charts (Categorical Factors vs. Survival Status):
1. **Diabetes-Survival Status**:
   - Negative (No Diabetes):
     - Survived: 45.82%
     - Died: 19.06%
   - Positive (With Diabetes):
     - Survived: 22.07%
     - Died: 13.04%
2. **Sex-Survival Status**:
   - Male:
     - Survived: 44.15%
     - Died: 20.74%
   - Female:
     - Survived: 23.75%
     - Died: 11.37%
3. **Smoking-Survival Status**:
   - Non-Smoker:
     - Survived: 45.82%
     - Died: 22.07%
   - Smoker:
     - Survived: 22.07%
     - Died: 10.03%
4. **Anaemia-Survival Status**:
   - Negative (No Anaemia):
     - Survived: 40.13%
     - Died: 16.72%
   - Positive (With Anaemia):
     - Survived: 27.76%
     - Died: 15.38%

---

## Visualizations

### Histograms:
- **Age vs. Survival Status**: Survival rates are highest in the 50-70 age group, with decreasing survival among older patients.
- **Platelets vs. Survival Status**: Distribution shows no significant difference between survivors and non-survivors.
- **Time vs. Survival Status**: Survival varies significantly based on time from diagnosis or treatment.
- **Ejection Fraction vs. Survival Status**: Higher survival rates are observed with ejection fractions above 40.

### Boxplots:
- **Age-Sex-Survival Status**: Highlights the age distribution across genders and survival outcomes.

### Scatter Plot:
- **Age-Time-Survival Status**: Visualizes the interplay between age and time, with survival marked distinctly.

### Histograms for Biochemical Markers:
- **Creatinine Phosphokinase vs. Survival Status**: No clear threshold differentiates survivors from non-survivors.
- **Serum Creatinine vs. Survival Status**: Elevated levels are associated with increased mortality.

---

## Purpose

The dashboard is intended for:
- Identifying risk factors that significantly impact survival.
- Providing insights to healthcare professionals for targeted interventions.
- Supporting research on heart failure outcomes.

---

## Usage

- Use the categorical charts to understand demographic and condition-specific survival patterns.
- Analyze the continuous variable histograms and scatter plots for thresholds and trends associated with survival.
- Leverage the insights for data-driven decision-making in clinical settings.

---

## Acknowledgments

This analysis is based on patient-level heart failure data. Special thanks to the contributors who provided the dataset and inspiration for this dashboard design.
