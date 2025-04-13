## Author
Carolina Cozzi
Mastery Project – Travel Tide Analysis
2025

# Travel_tide_project
Travel tide project is the results that I generate as final mastery project of my course in Data Analysis

## Project Overview

This project aims to investigate and identify customer segmentation in order to create personalized perks and incentives for a travel rewards program. By analyzing customer data, we can uncover behavioral patterns and group users into meaningful segments.

## Files & Structure
Project Folder/ 
│ 
├── README.md ← This file 
├── users_perks.csv ← CSV file with user-perk assignments 
├── Mastery_project.ppt ← Presentation of final results
│ 
├── ipynb/│ 
          └── Mastery_Project_CCozzi.ipynb ← Main Colab notebook


## Notebook Workflow

The Google Colab notebook follows this analytical pipeline:

1. Data Cleaning & Preparation: Handling missing values, data types, and basic preprocessing.
2. Exploratory Data Analysis (EDA): Visual exploration of customer behaviors and demographics.
3. Outlier Removal: Identifying and eliminating extreme values that may skew the clustering process.
4. Feature Scaling & PCA: Applying scaling techniques and Principal Component Analysis to reduce dimensionality.
5. Clustering: Using K-Means (unsupervised learning) to identify travel and demographic clusters among users.

## Tools & Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Setup Instructions

- Open the Colab notebook from the `/ipynb/` folder.
- Make sure to connect your Google Drive so the notebook can access and upload the CSV file:


```python
from google.colab import drive
drive.mount('/content/drive') 


