# Data Analysis with Python Internship - Task 4

**Author:** Rohit Kumar Verma  
**Email:** rohitkv2370@gmail.com

## Overview
This repository contains the solution for **Task 4** of the Data Analysis with Python Internship. The objective of this task is to perform data preparation, feature engineering, and create a dashboard of at least 5 distinct visualizations with corresponding insights using a Jupyter Notebook.

## Dataset Used
- **Name:** Titanic Dataset
- **Location:** `data/Titanic-Dataset.csv`
- **Description:** A classic dataset containing information about the passengers aboard the Titanic, including demographics, passenger class, fare, and whether they survived.

## File Structure
- `Task4_Titanic_Analysis.ipynb`: The main Jupyter Notebook containing the data cleaning, feature engineering, and visualizations.
- `data/`: Folder containing the CSV dataset to avoid hardcoding absolute paths.
- `images/`: Folder intended for exporting key figures (optional).
- `generate_notebook.py`: A script used to generate the `.ipynb` file.

## How to Run
1. Ensure you have Python installed along with the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
2. Navigate to the `Task 4` directory.
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `Task4_Titanic_Analysis.ipynb` and run the cells sequentially to reproduce the analysis and view the dashboard plots.

## Dashboard Highlights
The notebook includes 5 distinct charts:
1. **Histogram:** Distribution of Passenger Ages.
2. **Bar Chart:** Survival Rate by Passenger Class and Sex.
3. **Boxplot:** Distribution of Fare by Passenger Class.
4. **Scatterplot:** Age vs. Fare Colored by Survival.
5. **Heatmap:** Correlation of Numeric Variables.
