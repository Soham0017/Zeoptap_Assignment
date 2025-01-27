# Zeoptap Assignment

This repository contains the analysis and modeling of an eCommerce transactions dataset. The project is divided into three main tasks: Exploratory Data Analysis (EDA), Lookalike Model, and Customer Segmentation.

## Project Structure

- **EDA**: Analysis of customer, product, and transaction data to derive business insights.
- **Lookalike Model**: Recommends similar customers based on profile and transaction history.
- **Customer Segmentation**: Clustering techniques to identify distinct customer segments.

## Files

- `Customers.csv`: Contains customer information.
- `Products.csv`: Contains product details.
- `Transactions.csv`: Contains transaction records.
- `Soham_Gupta_EDA.ipynb`: Jupyter Notebook for EDA.
- `Soham_Gupta_Lookalike.ipynb`: Jupyter Notebook for Lookalike Model.
- `Soham_Gupta_Clustering.ipynb`: Jupyter Notebook for Customer Segmentation.
- `Soham_Gupta_Lookalike.csv`: Output of the Lookalike Model.
- `Soham_Gupta_EDA.pdf`: PDF report of EDA insights.
- `Soham_Gupta_Clustering.pdf`: PDF report of clustering results.

## Task 1: Exploratory Data Analysis (EDA)

- **Objective**: Analyze the dataset to derive business insights.
- **Deliverables**: Jupyter Notebook and PDF report.
- **Key Insights**:
  - Regional focus on South America.
  - Seasonal sales trends.
  - High-value customer targeting.

## Task 2: Lookalike Model

- **Objective**: Recommend similar customers based on profile and transaction history.
- **Method**: Used K-Nearest Neighbors (KNN) with cosine similarity.
- **Deliverables**: Jupyter Notebook and `Lookalike.csv`.

## Task 3: Customer Segmentation

- **Objective**: Segment customers using clustering techniques.
- **Method**: Used KMeans and DBSCAN algorithms.
- **Metrics**: Davies-Bouldin Index and Silhouette Score.
- **Deliverables**: Jupyter Notebook and PDF report.

## How to Run

1. Clone the repository.
2. Install required packages: `pandas`, , `matplotlib`, `seaborn`, `scikit-learn`.
3. Open the Jupyter Notebooks and run the cells to reproduce the analysis.

## Conclusion

This project provides insights into customer behavior and product performance, enabling targeted marketing strategies and improved customer engagement.
