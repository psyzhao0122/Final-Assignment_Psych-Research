## Religion and Public Religious Behavior: A Data Analysis Project

## Project Overview

This study investigates how religious affiliation, evangelical identity, and gender influence the frequency of religious service attendance, using a 2016 religion survey dataset sourced from Kaggle and FiveThirtyEight.
The analysis was conducted in Python and involved essential data science steps including data cleaning, missing value imputation, categorical variable recoding, and visualization. A chi-square test of independence was used to assess relationships between religious service attendance and predictor variables. Post-hoc standardized residual analysis further identified specific groups contributing significantly to observed associations.

## Aim of the Analysis
The primary goals of this analysis are:
1. To explore whether **present religion**, **evangelical identity**, and **gender** are significantly associated with how often individuals attend religious services.
2. To investigate how **age**, **income**, and **region** relate to public religious behaviors (e.g., praying publicly, wearing religious clothing).
3. To visualize frequency distributions and correlations among key behavioral variables.

## Data Source
- Dataset: [FiveThirtyEight Religion Survey](https://raw.githubusercontent.com/psyzhao0122/Final-Assignment_Psych-Research/main/religion-survey-results.csv)

## How to Run the Code

1. Open the Jupyter Notebook or Colab file: `Final_Assignment_ZiqingZhao.ipynb`
2. Run all cells from top to bottom.
3. The notebook will:
   - Load and clean the dataset
   - Recode categorical variables
   - Conduct statistical tests (chi-square)
   - Generate visualizations

## Short Summary of Results
Religious affiliation and evangelical identity were found to be significantly associated with religious service attendance, while gender showed no significant effect.
Faith-based groups such as Protestants and evangelicals reported higher participation, whereas agnostics and atheists had notably lower attendance.
Public religious expressions—such as praying in public or wearing religious clothing—were generally infrequent across the sample.
Age differences were observed: middle-aged individuals showed greater variability in public religious behaviors, while older adults reported very low engagement in wearing religious clothing.
These findings highlight the importance of targeted engagement strategies and can inform faith-based organizations and community planners in designing inclusive programs that address the varying religious behaviors across different demographic groups.

## Dependencies
Make sure the following Python libraries are installed:
```bash
pip install pandas numpy matplotlib seaborn scipy
