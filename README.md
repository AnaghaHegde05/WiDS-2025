## WiDS 2025: Integrated Academic Project

**Project Title:** Predicting ADHD Diagnosis and Biological Sex from fMRI Connectivity and Socio-Demographic Data

**Course Context:** 4th-Semester Exploratory Data Analysis (EDA)

**Collaboration:** Women in Data Science (WiDS) Datathon 2025

**Team:** 4 members

**Tools & Technologies:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## Project Overview

The project aimed to develop predictive models for:

1. **ADHD Diagnosis:** Classifying individuals as ADHD or non-ADHD.

2. **Biological Sex Prediction:** Classifying individuals as male or female.

**Data Sources:**

* **fMRI Connectivity Data:** Functional connectivity matrices representing brain activity.

* **Socio-Demographic Data:** Information such as age, education, and family background.

* **Emotional & Parenting Questionnaires:** Responses from standardised scales assessing emotional regulation and parenting styles.

## Data Preprocessing

* **fMRI Data:**

  * Applied Principal Component Analysis (PCA) to reduce dimensionality, retaining 99% of the variance.
  * This reduced the feature set from 19,900 to 1,188 components.

* **Socio-Demographic & Questionnaire Data:**

  * Handled missing values through imputation.
  * Encoded categorical variables using one-hot encoding.
  * Scaled numerical features to standardise the data.

## Model Development

* **Model Selection:** Implemented a Random Forest model for output.

* **Hyperparameter Tuning:** Utilised a hypermodel approach for optimising model parameters.

* **Class Imbalance Handling:** Applied techniques to address class imbalance in the dataset.

## Exploratory Data Analysis (EDA)

* **Correlation Analysis:** Identified high correlations among features to understand relationships.

* **Missing Values Visualisation:** Visualised missing data patterns to inform imputation strategies.
  
## Results

* **Model Performance:** Achieved high accuracy in predicting ADHD diagnosis and biological sex.

* **Feature Importance:** Identified key features influencing predictions, including specific brain connectivity patterns and questionnaire responses.

## Conclusion

This project provided valuable experience in handling complex, multi-modal data and developing predictive models. It highlighted the importance of data preprocessing, model interpretability, and addressing biases in machine learning applications.

For a comprehensive view of the project, please visit the [Google Sites page](https://sites.google.com/view/eel12anaghahegde/home).
