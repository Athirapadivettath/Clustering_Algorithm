# Clustering_Algorithm
# Clustering Assignment

## Objective
This project applies clustering techniques to the Iris dataset to group similar data points. The goal is to compare different clustering methods and visualize their results.

## Dataset
- The dataset used is the **Iris dataset**, loaded using `load_iris` from `sklearn.datasets`.
- It consists of four features describing iris flowers.

## Implementation Steps
1. **Loading and Preprocessing**
   - Load the dataset into a Pandas DataFrame.
   - Perform feature scaling using `StandardScaler`.
   
2. **Clustering Models**
   - **K-Means Clustering**: Groups data into 3 clusters.
   - **Hierarchical Clustering**: Uses Agglomerative Clustering to form hierarchical groups.
   - **Dendrogram**: Visualizes hierarchical clustering.

3. **Visualization**
   - Scatter plots to show clustering results.
   - Dendrogram to analyze hierarchical clustering structure.

## Results
- The performance of K-Means and Hierarchical Clustering is compared.
- Visualizations illustrate the clustering outcomes.

## Repository Structure
- `clustering_algorithm.ipynb` - Jupyter Notebook containing the implementation.
- `README.md` - This file describing the project.
  

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
