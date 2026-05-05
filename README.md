# Clinical Trial Data Analysis for a New Diabetes Medication

[Notebook Link](https://github.com/Kurodataio/diabetes-clinical-trial/blob/main/Clinical-Trial-Data-Analysis-New-Diabetes-Medication.ipynb)  

---

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits](#credits)  
- [License](#license)  

---

## Overview

PharmaTech, a leading pharmaceutical company. The company has recently completed a phase III clinical trial for a new type 2 diabetes medication

The request was to conduct a comprehensive analysis of PharmaTech's clinical trial data to evaluate the efficacy and safety profile of a new Type 2 diabetes medication.

---

## Dataset

- The dataset was provided by ITOnlinelearning.com 
- The dataset has 9 columns and 1400 rows
- The were no missing columns observed in the dataset 
- The **hba1c** column (feature) is central to the analysis  
- The "adverse_event" feature had over 80% null values and was dropped.

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Languages & Libraries:</strong> Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scipy, Sklearn</li>
  <li><strong>Tools:</strong> Jupyter Notebook, VS Code, Git, GitHub</li>
</ul>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn">
  <img src="https://img.shields.io/badge/Statsmodels-1A6E9A?style=for-the-badge&logo=statsmodels&logoColor=white" alt="Statsmodels">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
</p>
<P>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"/>  
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>
<p>
  <img src="https://img.shields.io/badge/MIT%20License-000000?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="MIT License">
</p>

---

## Installation

Step-by-step instructions to set up the project locally:

```bash

# Clone the repository
git clone https://github.com/Kurodataio/diabetes-clinical-trial.git

# Navigate to the project folder
cd diabetes-clinical-trial

# Launch Jupyter Notebook
jupyter notebook

```

## Usage

Instructions for using the project:

1. Open the main notebook (`Clinical-Trial-Data-Analysis-New-Diabetes-Medication.ipynb`)  
2. Run each cell sequentially or run ALL cells to reproduce the analysis  
3. Visualizations and results will be generated automatically  

---

## Analysis & Visualizations 
- exploratory data analysis (EDA) using pandas to assess data quality, distributions, and trends across treatment and placebo cohorts. 
![HbA1c Levels Over Time](images/HbA1c_Levels_Over_Time.png)

- Performed data cleaning and preprocessing in Python (Jupyter Notebook), including handling missing values, data type standardisation, and feature engineering (e.g. HbA1c change variable).

- Applied hypothesis testing techniques, including independent t-tests (p < 0.01), confirming statistically significant reductions in HbA1c levels for the treatment group compared to placebo.

- hypothesis testing techniques, including independent t-tests (p < 0.01), confirming statistically significant reductions in HbA1c levels for the treatment group compared to placebo


![HbA1c Reduction by Age Group and Gender](images/HbA1c_Reduction_by_Age_Group_&_Gender.png)

![HbA1c Reduction by Gender](images/HbA1c_Reduction_by_Gender.png)

![Most Common Adverse Events](images/adverse_events.png)

![Final HbA1c Levels: Treatment vs Placebo](images/Final_HbA1c_Levels-Treatment-vs-Placebo.png)

<!-- ![](images/.png) -->

<!-- ![](images/.png) -->


---

## Conclusion 

- Conducted ANOVA to evaluate differences in treatment effectiveness across demographic segments (age groups and gender).
- Performed chi-square tests of independence and built contingency tables to analyse adverse event frequencies, confirming no significant differences between groups
- There is variability in HbA1c outcomes among older (60+) and male cohorts, with consistent treatment efficacy across most demographics.
- There is no significant relationship between duration of diabetes and treatment effectiveness.
- The medication demonstrates statistically significant efficacy and a favourable safety profile, supporting recommendation for progression towards commercialisation (subject to regulatory approval). 

---

## Credits

<!-- - **Collaborators:** Name – [GitHub Profile](https://github.com/USERNAME)  
- **Dataset Source:** [Link](https://link-to-dataset.com)  
- **Tutorials / References:** [Link](https://link.com)   -->

- **Tutorials / References:** ITOnlinelearning.com 
- **Dataset Source:** ITOnlinelearning.com 
---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/). PharmaTech is a fictional company.  

---

