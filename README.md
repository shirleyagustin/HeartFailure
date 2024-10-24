# Mortality Caused by Heart Failure

# Project Overview

According to the [CDC](https://www.cdc.gov/heart-disease/data-research/facts-stats/index.html) heart disease is the leading cause of death for men, women, and people of most racial and ethnic groups. 
 
This project focuses on answering the following questions:

1. Does the risk of mortality increase with different CVD's?
    
2. What risk factors (variables) have more influence in predicting mortality caused by heart failure?
## Installation and Setup

### Codes and Resources Used

- **Editor Used:** Anaconda
- **Python Version:** Python 3.12.4

### Python Packages Used

- **Data Manipulation:** `pandas` `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`, `plotly express`
- **Machine Learning**: `scikit`

## Data
### Source Data

The data used in this project is from [Kaggle](https://www.kaggle.com/datasets/whenamancodes/heart-failure-clinical-records/data). The dataset contains 12 variables that can be used to predict mortality caused by heart failure. 

**Independent Variables:**

- Age: age of the patient (years)
- Anaemia: decrease of red blood cells or hemoglobin (boolean)
- High blood pressure: if the patient has hypertension (boolean)
- Creatinine phosphokinase (CPK): level of the CPK enzyme in the blood (mcg/L)
- Ejection fraction: percentage of blood leaving the heart at each contraction (percentage)
- Gender: woman or man (binary)
- Serum creatinine: level of serum creatinine in the blood (mg/dL)
- Serum sodium: level of serum sodium in the blood (mEq/L)
- Smoking: if the patient smokes or not (boolean)
- Platelets: platelets in the blood (kilo platelets/mL)
- Diabetes: if the patient has diabetes (boolean)

**Dependent Variables:** 

- Death event: if the patient died during the follow-up period (boolean)

**Definitions**:
- Serum Sodium:  If sodium levels drop too low, it can indicate that the heart is not working well enough to manage fluid balance.

- Creatinine Phosphokinase: CPK levels rise when there is damage to the muscles, including the heart. In heart failure, elevated CPK levels can indicate that the heart muscle is under stress or damaged

- Ejection fraction: Ejection fraction measures how well your heart pumps blood. In heart failure, a lower EF means the heart is pumping less blood with each beat

- Serum Creatinine: Serum creatinine is a marker of kidney function. In heart failure, high serum creatinine levels can indicate that the kidneys are struggling due to decreased blood flow from the heart.

- Increased Platelets: Sometimes, the body produces more platelets as a response to inflammation or stress related to heart failure.
  
- Decreased Platelets: In other cases, especially with severe heart failure, the platelet count might drop due to various factors like liver dysfunction or bone marrow problems.
## Results and evaluation

**Q1: Does the risk of dying increase with different CVD’s?**

Patients with high blood pressure have a higher risk of passing away than patients with diabetes. If you have both high blood pressure and diabetes you are at higher risk of passing away.


**Q2: What risk factors(variables) have more influence in predicting death caused by heart failure?**

Age, serum creatinine levels,  high blood pressure, and creatinine phosphokinase (CPK) are significant variables to predict heart failure.

## Future work

- Could have chosen a better data set as the model does not predict those who died as well as those who survived.

- P-value for certain variables, such as smoking, to assess the statistical significance of the predictor

- Explore a data set with more variables (ex. hyperlipidemia, obesity, excessive alcohol use)

## License

[MIT License](https://opensource.org/license/mit/)
