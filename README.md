 Titanic Survival Analysis - Python EDA

## Project Overview
Exploratory Data Analysis (EDA) on the Titanic dataset using Python,
investigating what factors determined passenger survival chances.

## Tools & Libraries Used
- Python
- Pandas (data cleaning & analysis)
- Matplotlib (visualizations)
- Seaborn (statistical charts)
- Jupyter Notebook

## Dataset
- 891 passengers, 12 columns
- Source: Kaggle Titanic Dataset

## Data Cleaning
- Filled 177 missing Age values with median age
- Filled 2 missing Embarked values with most common port
- Dropped Cabin column (77% missing values)

## Key Findings
- Overall survival rate was only **38.4%**
- **Women survived at 74.2%** vs men at only 18.9% 
  — women were 4x more likely to survive
- **1st class passengers survived at 62.9%** vs 
  3rd class at only 24.2% — wealth strongly affected survival
- Passengers around **age 29** had the highest survival count
- **Fare and Pclass** were the strongest factors 
  correlated with survival

## Visualizations
1. Overall Survival Rate (Pie Chart)
2. Survival by Gender (Bar Chart)
3. Survival by Passenger Class (Bar Chart)
4. Survival by Age (Histogram)
5. Correlation Heatmap

## How to Run
1. Clone this repository
2. Open `Titanic_EDA.ipynb` in Jupyter Notebook
3. Run all cells in order
