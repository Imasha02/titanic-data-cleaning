Titanic Dataset Cleaning and Exploration - focuses on cleaning and exploring the Titanic dataset using Python (Pandas, Seaborn, Matplotlib) in Google Colab.

## 📂 Project Overview

The Titanic dataset is a classic machine learning and data analysis problem. In this notebook, I performed:

- Data loading and initial inspection
- Null value detection and handling
- Categorical feature encoding
- Feature extraction (e.g., Deck from Cabin)
- Data visualization for comparison before and after cleaning

## 🧹 Data Cleaning Summary

| Feature     | Action Taken                                  |
|-------------|-----------------------------------------------|
| `Age`       | Filled missing values with mean               |
| `Embarked`  | Dropped 2 rows with missing values            |
| `Cabin`     | Created new `Deck` feature; nulls set as `'U'`; later dropped `Cabin` |
| `Sex`       | Left as is (used in analysis)                 |
| `Survived`  | Used for comparison/visualization             |

## 📊 Key Visualizations

- Grouped bar chart: `Sex` vs `Survived` (percentages)
- Box plot: Age distribu-tion before vs after filling nulls
- Bar plot: Survival by Deck

## 📁 Files Included

- `Titanic_dataset_cleaning.ipynb`: The full Colab notebook
- `train.csv`: Original dataset (Kaggle Titanic dataset)

## 🚀 Tools Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab  


