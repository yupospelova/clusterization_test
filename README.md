# Clusterisation of spatial sequence data

Test task for the BGI Junior Algorithm Developer position. 

## Contents
This project contains *BGI_clusterization_task.ipynb* notebook and presentation. 

The pipeline consists of these steps: 

0) Literature review, 
1) Data Exploration; 
2) Dimension Reduction
3) Clusterization

3 methods of __Dimension Reduction__ were used: Principal Component Analysis (__PCA__), t-Distributed Stochastic Neighbor Embedding (__t-SNE__), and Uniform Manifold Approximation and Projection (__UMAP__). 

3 algorithms of __Clusterization__ were used:
1) __KMeans__ clustering
2) __Agglomerative__ clustering
3) __DBSCAN__ clustering

Results of this proejct are explained in *BGI_test_presentation.pdf* file. 

## Requirements
The proejct was done in Google Colab. 

Here are the requirements:

```bash
matplotlib == 3.2.2
numpy == 1.21.6
pandas == 1.3.5
plotly == 5.5.0
scikit_learn == 1.0.2
scipy == 1.7.3
seaborn == 0.11.2
umap_learn == 0.5.3
```
