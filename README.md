# Global-Happiness-Data
# Happiness Dataset – Data Cleaning and Preprocessing

 Overview
This repository contains the Happiness dataset, which has been cleaned and preprocessed for analysis. The dataset originally consisted of multiple smaller datasets, which were combined into a single master dataset to ensure consistency and completeness. It includes information about countries’ happiness rankings across different years, with columns for `index`, `rank`, `year`, and `country`.

The data cleaning and preprocessing workflow involved several steps. First, the smaller datasets were merged to form a unified dataset. Missing values were then handled: rows with critical missing information in `country`, `year`, or `rank` were deleted, while other missing entries were filled where appropriate. Duplicate rows were identified and removed to maintain data integrity. Next, text standardization was performed, converting all country names to Title Case to ensure uniformity. The dataset was then sorted alphabetically by `country` to improve readability, while keeping `index`, `rank`, and `year` correctly aligned. Finally, data types were converted where necessary, with `index`, `rank`, and `year` set as integers.

The final output is a cleaned and standardized dataset, available in this repository as WorldHappiness 2013-2023.csv
. The repository also contains the original raw datasets in the `raw_data/` folder and the Jupyter Notebook or Excel file used for preprocessing in the `notebooks/` folder. All files are organized for easy access and reference.

The repository structure is simple and intuitive. The `raw_data/` folder contains the original smaller datasets before preprocessing. The `cleaned_data/` folder contains the final cleaned and combined dataset. The `notebooks/` folder includes the Jupyter Notebook or Excel file that documents all preprocessing steps, transformations, and cleaning procedures. Finally, the README.md provides a detailed explanation of the dataset and the workflow applied.

This cleaned dataset can be used for various purposes, including data analysis, visualization, statistical modeling, and research on global happiness trends. The dataset maintains proper alignment after sorting, ensuring that `rank`, `year`, and `index` correspond correctly to each country. By providing both the raw and cleaned data along with preprocessing documentation, this repository enables reproducibility and facilitates a smooth analysis workflow.

