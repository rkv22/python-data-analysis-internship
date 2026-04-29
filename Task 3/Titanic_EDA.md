# Task 3: Titanic Dataset Exploratory Analysis

## Overview
This project (Task 3 of the Data Analysis Internship) contains a mini Exploratory Data Analysis (EDA) of the Titanic dataset. The main objective of this analysis is to understand the factors affecting passenger survival on the Titanic by cleaning the data, engineering new features, and generating insightful visualizations.

## Project Structure
- `Titanic-Dataset.csv`: The original Titanic dataset containing passenger information.
- `Titanic_Mini_EDA.ipynb`: A Jupyter Notebook containing the data cleaning, feature engineering, and exploratory data analysis.

## Workflow

### 1. Data Cleaning
- Missing values in the `Age` column were imputed using the mean age.
- Irrelevant columns that do not contribute significantly to survival analysis (`PassengerId`, `Name`, `Ticket`, and `Cabin` due to high missing values) were removed.
- Missing values in the `Embarked` column were filled with the mode.

### 2. Feature Engineering
- **FamilySize**: A new feature created by combining `SibSp` (siblings/spouses) and `Parch` (parents/children) plus the passenger themselves.
- **AgeGroup**: Passengers were categorized into age groups: `Child (0-12)`, `Teen (13-18)`, `Young Adult (19-35)`, `Adult (36-60)`, and `Senior (60+)`.

### 3. Exploratory Data Analysis (EDA) & Visualizations
The notebook answers several key questions regarding survival:
- **Age Distribution**: A histogram visualizing the age distribution of passengers.
- **Survival Rate by Age Group**: A bar plot showing which age groups had the highest survival rates.
- **Survival Rate by Embarkation Port**: A visualization analyzing the survival rates based on where passengers boarded the ship (Cherbourg, Queenstown, Southampton).
- **Survival Rate by Family Size**: An analysis exploring whether traveling alone or with family influenced the chances of survival.

## Requirements
To run the Jupyter Notebook, you need the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## How to Run
1. Ensure you have Jupyter Notebook or JupyterLab installed.
2. Clone or download this repository.
3. Open `Titanic_Mini_EDA.ipynb` and execute the cells sequentially to reproduce the analysis and visualizations.

## Author
- **Rohit Kumar Verma**
