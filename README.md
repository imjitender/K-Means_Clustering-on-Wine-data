# K-Means_Clustering-on-Wine-data
This Jupyter Notebook  demonstrates the process of performing K-Means clustering on the Wine dataset from sklearn.datasets. The goal is to find the optimal number of clusters (K) for the dataset.

Project Description
The notebook follows a standard machine learning workflow for unsupervised learning tasks:

Data Loading: The Wine dataset is loaded directly from sklearn.datasets.

Feature Scaling: The data is scaled using StandardScaler to ensure that all features contribute equally to the distance calculations, which is crucial for K-Means.

Determining the Optimal Number of Clusters (K): Two common methods are used to find the best value for K:

Elbow Method (WCSS): This method plots the within-cluster sum of squares (WCSS) for a range of K values. The "elbow" of the curve, where the rate of decrease in WCSS slows down, is often chosen as the optimal K.

Silhouette Score: The silhouette score measures how well each data point fits into its assigned cluster. A higher score indicates better-defined clusters. The notebook calculates and plots the silhouette score for each K.

Visualization: The results of the Elbow and Silhouette methods are visualized using matplotlib.pyplot to help in the selection of the best K.

Setup
To run this notebook, you will need the following Python libraries installed:

scikit-learn

matplotlib

numpy

You can install these dependencies using pip:

pip install scikit-learn matplotlib numpy

