# Music Genre Classification Using PCA

This project classifies music tracks by genre using **Principal Component Analysis (PCA)** for dimensionality reduction and **Logistic Regression** for supervised classification. The aim is to analyze various musical features and determine genre patterns, enhancing data management and classification accuracy.

## Project Overview

With the growth of digital streaming, categorizing and recommending music based on genre has become essential. This project involves:
- **Data Exploration**: Understanding dataset structure and feature distribution.
- **Correlation Analysis**: Identifying relationships between features.
- **PCA for Dimensionality Reduction**: Reducing feature redundancy to improve model performance.
- **Classification**: Using logistic regression on PCA-transformed data to predict genres for unlabeled tracks.

## Project Structure

- **Data**: 
  - `music_dataset_mod.csv` - Dataset with musical features.
  - `Music Data Legend.xlsx` - Legend for feature explanations.
- **Notebook**: 
  - `Music Genre Classification with PCA - Project.ipynb` - Main notebook containing code and analysis.
  
## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook

### Libraries Required

```bash
pip install pandas numpy matplotlib scipy scikit-learn seaborn
```

### Running the Project

1. Open the `Music Genre Classification with PCA - Project.ipynb` file in Jupyter Notebook.
2. Follow the steps for data exploration, PCA, and classification.

## Project Files

- **`music_dataset_mod.csv`**: Main dataset with features.
- **`Music Data Legend.xlsx`**: Legend for dataset features.
- **`Music Genre Classification with PCA - Project.ipynb`**: Jupyter Notebook with code for the project.

## Key Concepts

- **Principal Component Analysis (PCA)**: Reduces feature dimensions to simplify data and enhance model accuracy.
- **Logistic Regression**: A supervised learning model for predicting genres based on PCA-transformed data.

## Results

The project evaluates classification accuracy with PCA-transformed data vs. original data, showing PCA’s effectiveness in improving performance by reducing feature noise.


---
