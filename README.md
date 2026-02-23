Please find attached my notebook titled **“Transaction Patterns – Unsupervised Learning Analysis.”** Below is a brief explanation of the methodology, approach, and insights derived from the analysis.

### 1. Objective of the Notebook

The objective of this project is to analyze transaction-related data and identify hidden behavioral patterns using **unsupervised machine learning techniques**. Since the dataset does not contain labeled outcomes, clustering algorithms were used to segment the transactions into meaningful groups.

### 2. Data Understanding and Preparation

The dataset was first explored to understand its structure, features, and overall distribution. The initial analysis included reviewing data types, identifying relevant variables, and preparing the dataset for modeling.

Key preparation steps included:

* Exploring the dataset to understand feature characteristics.
* Selecting relevant numerical variables suitable for clustering analysis.
* Organizing the dataset for further machine learning processing.

### 3. Feature Selection

Only numerical features were selected for clustering because distance-based algorithms such as K-Means operate effectively on numerical data. These features represent transaction patterns and behavioral indicators that help differentiate groups within the dataset.

### 4. Clustering Approach

The primary algorithm used in this analysis is **K-Means Clustering**, which groups data points based on similarity.

The following steps were performed:

* Applied K-Means clustering to segment the transactions.
* Experimented with different numbers of clusters to observe data grouping.
* Assigned cluster labels to each data point to analyze behavioral patterns across clusters.

### 5. Cluster Evaluation

To evaluate the effectiveness of clustering, the **Silhouette Score** was used. This metric measures how well each observation fits within its assigned cluster compared to other clusters. A higher score indicates better-defined and well-separated clusters.

### 6. Dimensionality Reduction

To better understand and visualize the structure of the dataset, dimensionality reduction techniques were applied.

**Principal Component Analysis (PCA)**

* Used to reduce the dimensionality of the dataset while retaining most of the important information.
* Helped simplify the data representation for analysis.

**t-SNE (t-Distributed Stochastic Neighbor Embedding)**

* Used to visualize high-dimensional data in a two-dimensional space.
* Provided a clearer representation of cluster formation and data distribution.

### 7. Visualization and Cluster Observations

From the visualization results, distinct clusters are visible in the dataset, indicating that the data naturally forms different behavioral segments.

Key observations include:

* Multiple clusters are clearly separated, suggesting meaningful grouping within the transaction data.
* Some clusters appear dense, indicating transactions with very similar characteristics.
* Certain clusters are more spread out, which may represent varied behavior within that segment.
* The visual separation of clusters confirms that the clustering algorithm captured underlying patterns effectively.

These clusters may represent different types of transaction behaviors such as:

* High transaction activity patterns
* Regular transaction behavior
* Low or infrequent transaction activity
* Potentially unusual or distinct transaction patterns

### 8. Key Outcome

The analysis successfully identified distinct groups within the dataset using unsupervised learning techniques. These clusters provide insights into how transaction behaviors differ across the dataset and can support further analysis such as behavioral segmentation, anomaly detection, or risk identification.

### 9. Tools and Technologies Used

The analysis was performed using the following tools:

* Python
* Pandas and NumPy for data processing
* Scikit-learn for machine learning models
* PCA and t-SNE for dimensionality reduction
* Visualization libraries for cluster analysis

### 10. Summary

This notebook demonstrates a complete workflow for exploratory data analysis and unsupervised learning. By applying clustering and visualization techniques, the analysis uncovers hidden structures in transaction data and highlights meaningful behavioral patterns within the dataset.

