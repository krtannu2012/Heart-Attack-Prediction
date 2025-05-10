# Heart Attack Risk Prediction Project

## Overview
This project aims to predict the risk of heart attack in patients based on various health indicators and lifestyle factors. Using machine learning techniques, the model analyzes features such as gender, smoking habits, blood pressure, obesity, and other medical conditions to identify individuals at risk of heart attacks.

## Kaggle Project
You can view and interact with the project on Kaggle: [Heart Attack Prediction on Kaggle](https://www.kaggle.com/code/kumaritannu20/up-to-date-heart-attack-analysis-and-predictions).

## Dataset Description
The project uses two primary datasets:

1. **Training Dataset (`Train.csv`)**: 
   - Contains health data with the target variable "UnderRisk" indicating whether a patient is at risk of a heart attack
   - Features include: Gender, Chain_smoker, Consumes_other_tobacco_products, HighBP, Obese, Diabetes, Metabolic_syndrome, etc.

2. **Testing Dataset (`Test.csv`)**: 
   - Similar features as the training dataset but without the target variable
   - Used to make predictions that can be submitted in the required format

## Features
The dataset includes the following features:
- **Gender**: Biological gender of the patient (1 = Male, 2 = Female)
- **Chain_smoker**: Whether the person is a habitual smoker (0 = No, 1 = Yes)
- **Consumes_other_tobacco_products**: Usage of tobacco products other than cigarettes (0 = No, 1 = Yes)
- **HighBP**: Presence of high blood pressure (0 = No, 1 = Yes)
- **Obese**: Whether the patient is classified as obese (0 = No, 1 = Yes)
- **Diabetes**: Presence of diabetes (0 = No, 1 = Yes)
- **Metabolic_syndrome**: Presence of metabolic syndrome (0 = No, 1 = Yes)
- **Use_of_stimulant_drugs**: Usage of stimulant drugs (0 = No, 1 = Yes)
- **Family_history**: Family history of heart disease (0 = No, 1 = Yes)
- **History_of_preeclampsia**: History of preeclampsia (0 = No, 1 = Yes)
- **CABG_history**: History of Coronary Artery Bypass Grafting surgery (0 = No, 1 = Yes)
- **Respiratory_illness**: Presence of respiratory illness (0 = No, 1 = Yes)

## Target Variable
- **UnderRisk**: Whether the patient is at risk of a heart attack (yes/no)

## Analysis Methodology
The analysis is conducted through various stages as described in the Jupyter notebook `up-to-date-heart-attack-analysis-and-predictions.ipynb`:

1. **Introduction**:
   - Overview of heart attacks and their medical implications
   - Understanding the variables in the dataset

2. **Data Preparation**:
   - Loading required Python libraries
   - Initial analysis of the dataset
   - Examining missing values and unique values
   - Separating variables into numerical and categorical

3. **Exploratory Data Analysis (EDA)**:
   - Univariate analysis with distribution plots for numerical variables
   - Categorical variable analysis with pie charts
   - Bivariate analysis between features and the target variable
   - Correlation analysis using heatmaps

4. **Data Preprocessing**:
   - Handling outliers
   - Feature scaling with RobustScaler
   - One-hot encoding for categorical variables
   - Train-test split

5. **Modeling**:
   - Logistic Regression
   - Decision Tree
   - Support Vector Machine
   - Random Forest
   - Hyperparameter optimization using GridSearchCV
   - Model evaluation with cross-validation

## Usage
To use this project:

1. **Explore the Data**:
   - Review the training and testing datasets
   - Understand the features and their implications for heart attack risk

2. **Run the Analysis**:
   - Open `up-to-date-heart-attack-analysis-and-predictions.ipynb` in Jupyter Notebook or VS Code
   - Execute the cells to see the analysis and model building process
   - Review the visualizations to understand data patterns

3. **Make Predictions**:
   - Apply the trained models to the test dataset
   - Generate predictions in the format of `Sample_Submission.xlsx`

## Instructions
- Make sure to install all required libraries listed in the Requirements section
- Run the cells in the Jupyter notebook in sequence to ensure all dependencies are properly loaded
- The notebook contains detailed comments explaining each step of the analysis and modeling process

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - jupyter

## Future Improvements
- Feature engineering to create more predictive variables
- Ensemble methods to combine multiple model predictions
- Deep learning approaches for potentially higher accuracy
- Web application for real-time heart attack risk assessment

## License
This project is available for educational and research purposes.

## Author
Kumari Tannu

## Acknowledgments
- Medical literature on heart attack risk factors
- Machine learning community for algorithm implementations
- Kaggle platform for hosting the project and dataset
