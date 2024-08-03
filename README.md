# Customer Clustering
This project focuses on clustering wholesale customers based on their purchasing patterns. Using the DBSCAN algorithm, the project identifies and visualizes different customer segments to provide insights into customer behavior.

# Project Overview
The project involves loading and preprocessing wholesale customer data, exploring the data through visualizations, and then applying the DBSCAN clustering algorithm to segment the customers. The results are analyzed and visualized to gain insights into the distinct groups identified by the clustering process.

# File Structure
* [wholesale_customer_clustering.ipynb](https://github.com/shrek-28/customer-clustering/blob/main/Wholesale%20Customer%20Clustering.ipynb): This is the main Python script that contains all the steps for data loading, preprocessing, exploration, clustering, and visualization.

# Dataset
The dataset used in this project includes information about wholesale customers and their annual spending on various product categories like Milk, Grocery, and Detergents_Paper. It also includes categorical features like ```Channel``` and ```Region```

# Key Steps in the Project
* Data Loading and Exploration:
    * Load the dataset using Pandas.
    * Explore the data with ```head()``` and ```info()``` methods to understand the structure and content of the dataset.
* Data Visualization:
   * Use Seaborn to create scatter plots, histograms, and cluster maps to visualize relationships between features like Milk, Grocery, and Channel.
   * Generate a pair plot to examine feature distributions and relationships based on the Region.
* Data Preprocessing:
   * Scale the data using StandardScaler to standardize the features for clustering.
* Clustering with DBSCAN:
   * Implement the DBSCAN algorithm to identify clusters in the standardized data
   * Experiment with different eps values to determine the percentage of outliers.
   * Visualize the resulting clusters using scatter plots.
* Cluster Analysis:
   * Assign cluster labels to the original data.
   * Calculate the mean values of the features for each cluster and visualize these means using a heatmap.

# Dependencies
To run this project, you need the following Python libraries:
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
You can install these libraries using pip:
```
pip install numpy pandas matplotlib seaborn scikit-learn
```

# Running the Project
* Clone the repository:
```
git clone https://github.com/yourusername/wholesale-customer-clustering.git
cd wholesale-customer-clustering
```
* Launch Jupyter Notebook:
``` jupyter notebook ```
* Open the [wholesale_customer_clustering.ipynb](https://github.com/shrek-28/customer-clustering/blob/main/Wholesale%20Customer%20Clustering.ipynb) notebook and run the cells sequentially to execute the full analysis.

# Results and Insights
The notebook segments customers into distinct clusters based on their purchasing behavior. The resulting visualizations and cluster analysis provide valuable insights into the different customer groups, which can inform targeted marketing and business strategies.

# Future Work
* Experiment with different clustering algorithms like K-Means and Agglomerative Clustering.
* Incorporate additional data features to enhance clustering results.
* Deploy the clustering model in a web application for real-time customer segmentation.
