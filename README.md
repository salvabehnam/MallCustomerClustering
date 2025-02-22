# 🛍️ Mall Customer Clustering

This project applies **unsupervised machine learning** techniques to segment mall customers based on their purchasing habits and demographic information. By identifying distinct customer groups, businesses can tailor marketing strategies to enhance customer engagement and sales.

## 📌 Features 

- **Data Preprocessing**: Handling missing values and performing basic data cleaning.
- **Clustering Algorithms**: Implementing K-Means and DBSCAN to identify customer segments.
- **Optimal Cluster Determination**: Utilizing the "elbow method" to find the optimal number of clusters for K-Means.
- **Visualization**: Plotting clusters to interpret and understand customer segments.

## 📂 Project Structure

    MallCustomerClustering/
    ├── README.md
    ├── Mall_Customers.csv    # Dataset containing customer information
    ├── Kmeans.ipynb          # Jupyter Notebook for K-Means clustering
    ├── DBSCAN.ipynb          # Jupyter Notebook for DBSCAN clustering
    └── Init.ipynb            # Initialization and data exploration



## 📊 Dataset

The dataset `Mall_Customers.csv` includes the following columns:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Customer's gender.
- **Age**: Customer's age.
- **Annual Income (k$)**: Annual income of the customer in thousand dollars.
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature.

## ✨ Technologies Used

- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **scikit-learn**: Machine learning library for implementing clustering algorithms.
- **Matplotlib**: Data visualization.
- **Jupyter Notebook**: Interactive environment for executing and visualizing code.

