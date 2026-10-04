# Yuva-intern-Week1-task
Week 1 Task: Data Acquisition, Cleaning, and Preprocessing on Titanic Dataset
## Overview
This repository contains the data acquisition, exploratory data analysis, and preprocessing workflow for the Titanic dataset using Python.

## Key Steps Performed:
- **Data Acquisition**: Loaded Titanic dataset via Seaborn.
- **Handling Missing Values**: Imputed numerical features (Age) with median, categorical features (Embarked, Embark Town) with mode, and dropped high-missingness columns (Deck).
- **Outlier Capping**: Capped extreme values in 'Fare' using the Interquartile Range (IQR) method.
- **Encoding**: Converted categorical variables ('Sex') into binary format (0 for Male, 1 for Female).
- **Verification**: Verified zero residual null values across all features.

