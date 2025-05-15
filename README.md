# Customer Segmentation for Credit Card Users

This project applies unsupervised machine learning techniques to segment credit card customers into meaningful clusters. The goal is to understand different customer behaviors and provide data-driven business insights.

## 📁 Files Included

* `Customer_Segmentation_Credit_Card_Project.ipynb`: The main Jupyter notebook with all steps including data cleaning, clustering, and visualization.
* `cc general.csv`: The original dataset from Kaggle containing customer credit card information.
* `clustered_customers.csv`: Dataset with an additional column representing the assigned cluster for each customer.
* `cluster_profile.csv`: A summary CSV showing the average feature values for each cluster.
* `report.docx` / `report.pdf`: Full written report with findings, visualizations, and business insights.
* **Power BI Dashboard Files:**

  * `Customer_Segmentation_Dashboard.pbix`: Power BI dashboard file for interactive exploration of the segmentation results.
  * `Customer_Segmentation_Dashboard.pdf`: Exported PDF version of the Power BI dashboard for quick review and sharing.

## 📊 Objective

* Understand and explore the dataset
* Determine the optimal number of customer clusters
* Perform customer segmentation using clustering
* Analyze and profile each cluster
* Derive actionable business insights
* Visualize segmentation results with a Power BI dashboard

## 🚀 Key Steps

1. **Data Exploration & Preprocessing**

   * Handling missing values
   * Feature scaling and transformation

2. **Finding Optimal Clusters**

   * Elbow method
   * Silhouette score analysis

3. **Customer Segmentation**

   * K-Means clustering
   * Cluster labeling and visualization

4. **Cluster Profiling**

   * Interpretation of each cluster
   * Summary statistics and behavioral patterns

5. **Business Insights & Recommendations**

   * How businesses can target different segments
   * Suggestions for improving customer retention and engagement

6. **Dashboard Visualization**

   * Interactive Power BI dashboard for in-depth exploration of clusters and metrics

## 📌 Insights

* The segmentation revealed clusters such as:

  * High spenders with low balance
  * Customers with high revolving balance but low payments
  * Low-activity or dormant users
  * Loyal and consistent customers

## 📎 Dataset Source

* [Kaggle - Customer Segmentation Credit Cards](https://www.kaggle.com/code/des137/customer-segmentation-credit-cards)

## 📈 Tools & Libraries

* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* Power BI Desktop (for dashboard creation)

## 📃 Report

The complete project report is available in both DOCX and PDF formats inside this repo.
