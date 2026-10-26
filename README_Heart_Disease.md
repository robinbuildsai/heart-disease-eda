# Heart Disease Analysis — Exploratory Data Analysis

## Project Overview
This project explores a heart disease dataset using Python and data visualization. It examines patient characteristics and how selected features relate to the `HeartDisease` target.

## Objectives
- Inspect the dataset structure, summary statistics, missing values, and duplicates.
- Explore distributions of key numerical features.
- Analyze heart disease status by sex, chest pain type, and fasting blood sugar.
- Examine cholesterol patterns and numeric correlations.
- Clean selected zero-coded values and demonstrate categorical encoding and feature scaling.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- Jupyter Notebook

## Repository Files
- `Heart_Disease_EDA.ipynb` — organized notebook containing the analysis and visualizations.
- `heart.csv` — input dataset (add only if you have permission to redistribute it).

## How to Run
1. Download or clone this repository.
2. Place `heart.csv` in the same directory as the notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. Open `Heart_Disease_EDA.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the notebook cells from top to bottom.

## Data Cleaning and Preprocessing
The notebook treats zero values in `Cholesterol` and `RestingBP` as potential placeholders and replaces them with the mean of the non-zero values. This assumption should be checked against the dataset documentation before using the data for modeling.

Categorical variables are one-hot encoded, and selected numerical features are standardized. For a predictive machine-learning workflow, fit preprocessing steps only on the training data to avoid data leakage.

## Limitations
- Findings describe associations in the dataset and do not prove causation.
- Data-cleaning assumptions may affect results.
- This project is for learning and exploratory analysis only; it is not a clinical diagnostic tool.

## Author
Created by [robinbuildsai](https://github.com/robinbuildsai)
