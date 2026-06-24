# PRODIGY_ML_02

# Customer Segmentation using K-Means Clustering

## Overview

This project was completed as part of the **Machine Learning Internship at Prodigy InfoTech**. The objective is to group retail store customers into different segments based on their purchasing behavior using the **K-Means Clustering Algorithm**.

## Dataset

Dataset: Mall Customers Dataset

Source: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Features Used

- Annual Income (k$)
- Spending Score (1-100)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Structure

```text
PRODIGY_ML_02
│
├── customer_segmentation.py
├── Mall_Customers.csv
├── README.md
├── requirements.txt
├── elbow_method.png
└── customer_clusters.png
```

## Methodology

1. Load and explore the dataset.
2. Select relevant customer features.
3. Use the Elbow Method to find the optimal number of clusters.
4. Apply K-Means Clustering.
5. Visualize customer segments and cluster centroids.

## Results

The model successfully grouped customers into distinct segments based on income and spending patterns, helping identify different customer behaviors for targeted marketing strategies.

## Output Files

- `elbow_method.png` – Elbow Method graph
- `customer_clusters.png` – Customer segmentation visualization

## How to Run

```bash
pip install -r requirements.txt
python customer_segmentation.py
```

## Learning Outcomes

- Unsupervised Machine Learning
- K-Means Clustering
- Customer Segmentation
- Elbow Method
- Data Visualization

## Internship Details

**Organization:** Prodigy InfoTech  
**Track:** Machine Learning  
**Task:** Task-02 – Customer Segmentation using K-Means Clustering

## Author

**Aravind V**
