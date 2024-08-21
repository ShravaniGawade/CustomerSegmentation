# Customer Segmentation for Credit Card Users

Project Overview
This project focuses on segmenting 9,000 credit card users into distinct clusters to better understand customer behavior and enhance targeted marketing strategies. The segmentation was performed using the KMeans clustering algorithm, along with the Elbow Method to determine the optimal number of clusters. Principal Component Analysis (PCA) was applied to reduce the dimensionality of the dataset from 18 to 2, enabling effective visualization of the clusters.

Project Structure
Data Preparation: Preprocessed the data, including handling missing values, normalizing features, and selecting relevant attributes for clustering.
KMeans Clustering: Implemented the KMeans algorithm and utilized the Elbow Method to identify 7 optimal clusters.
Dimensionality Reduction: Conducted PCA to reduce dimensionality and facilitate the visualization of clusters.
Visualization: Created scatter plots to visualize the customer clusters in 2D space.

Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn (KMeans, PCA)
- Matplotlib
- Seaborn

Results
Successfully segmented 9,000 credit card users into 7 clusters.
Reduced dimensionality using PCA, making it easier to interpret and visualize customer segments.
Provided insights into different customer behaviors, which can be used for targeted marketing and personalized services.

Future Work
Explore other clustering techniques, such as DBSCAN or Hierarchical Clustering, for comparison.
Conduct deeper analysis of each cluster to identify specific customer characteristics.
Implement clustering in a production environment for real-time customer segmentation.
