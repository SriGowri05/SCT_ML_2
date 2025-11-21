# SCT_ML_2(Customer Segmentation Using K-Means Clustering)

## Overview
This project groups customers into segments using a K-Means Clustering model.
The segmentation is based on two main features:
- Annual Income (k$)
- Spending Score (1–100)

The project was completed in Google Colab for an internship task at SkillCraft Technology.

## Project Structure
- datasets/
  - Mall_Customers.csv
- SCT_ML_2.ipynb
- README.md


## Dataset
The dataset contains customer demographic and spending-related features.
The clustering is performed using the following columns:
- Annual Income (k$)
- Spending Score (1–100)

Files inside the dataset folder:
- Mall_Customers.csv

## Data Cleaning
The following preprocessing steps were performed:
-Selected required numeric columns
-Checked and handled missing values (if any)
-Applied the Elbow Method to determine the suitable number of clusters

## Visualizations
The notebook contains:
-Elbow Method plot
-Scatter plot showing grouped customer clusters

## Model Used
K-Means Clustering

Steps:
1.Load dataset
2.Select features
3.Apply Elbow Method
4.Train K-Means model
5.Predict customer clusters
6.Visualize cluster groups  

## How to Run
1. Open Google Colab.
2. Upload the `SCT_ML_2.ipynb` file.
3. Upload the `dataset/` folder.
4. Run all cells to see outputs.

## Author
SriGowri
