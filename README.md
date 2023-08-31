# Exploring-Hypertension-related-Genes-and-Diseases
This project aims to explore the relationships between hypertension-related genes and diseases using data analysis, knowledge graph visualization, and machine learning techniques. The main steps of the project are as follows:

Data Preprocessing and Exploration:

Gene data is loaded from an Excel file ('BP_genes.xlsx'), and basic data exploration is performed to understand the structure of the gene dataset.
Identifying Hypertension-related Diseases:

Disease data is loaded from three CSV files ('mondo_terms.csv', 'orphanet.csv', 'umls.csv').
The script filters and identifies diseases related to hypertension using textual matching.
The resulting hypertension-related disease names are stored in the variable 'Hypertension_mondo.'
Knowledge Graph Generation:

A knowledge graph is generated using disease and gene data, with relationships connecting diseases to related genes.
The graph visualization is performed for each cluster of hypertension-related diseases.
Machine Learning for Clustering:

Features from the disease-gene relationships are preprocessed and transformed using one-hot encoding and TruncatedSVD (dimensionality reduction).
The script applies K-means clustering to group the diseases based on the selected features.
The optimal number of clusters is determined using the Elbow Method and Silhouette Score.
Visualization and Analysis:

The clustered diseases are visualized using a scatter plot, with each cluster represented by different colors.
The script analyzes the relationships between hypertension and anti-hypertensive drugs using an oval diagram.
The occurrences of hypertension-related diseases in the dataset are counted and stored in a CSV file ('occurence.csv').
The project provides insights into the associations between hypertension-related genes and diseases, visualizes these relationships in knowledge graphs, and clusters the diseases based on their features. The results can help researchers and medical professionals gain a better understanding of hypertension-related conditions and potential therapeutic targets for anti-hypertensive drugs.


The Data can be retrieved from https://drive.google.com/drive/folders/1B0oYERWyp-1GVKEqOhuy0CGgRgwnGYf6?usp=sharing


Cluster wise analysis, example of Cluster 1 : CLuster analysis/all.tgahpzyj7
