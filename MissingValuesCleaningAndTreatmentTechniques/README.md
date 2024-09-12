# Data Cleaning and Missing Values Treatment Techniques

## Project Overview

This project aims to explore and apply various data cleaning strategies on a set of historical records provided by a company in the telecommunications sector. The dataset contains approximately 150,000 records with variables that require treatment for missing values, outliers, and other inconsistencies. The cleaned data will be subsequently used for predictive modeling by the company's responsible sector.

## Dataset

- **Source**: Historical data from the telecommunications company.
- **Size**: Approximately 150,000 records.
- **Description**: The dataset includes a dictionary with the description of each variable, allowing for a more detailed understanding of each field.

## Objectives

- Perform data cleaning and treatment to correct missing values and outliers.
- Generate a new CSV file with the cleaned data, which can be used for future predictive modeling.
- Document the treatment and cleaning process to ensure replicability and understanding of the procedures performed.

## Analysis Techniques

- **Identifying Missing Values**: Mapping and initial analysis of missing values present in the dataset.   
- **Dropping Columns**: Removing entire columns with a high proportion of missing values that do not add significant value to the analysis.
- **Backward Fill Imputation**: Replacing missing values based on subsequent values in the same series.
- **Forward Fill Imputation**: Replacing missing values based on previous values in the same series.
- **Categorical Variable Imputation**: Filling in missing values in categorical variables with the mode or using specific categorical imputation methods.
- **Dropping Rows**: Excluding rows with missing values when imputation is not feasible or may distort the results.
- **Outlier Identification**: Using statistical techniques and visualizations to identify outliers that could negatively impact future analyses.  
- **Outlier Treatment**: Applying methods such as transformation based on criteria defined by decision-makers.
