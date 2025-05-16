# prodigy_ML_TASK2
 KMeans Clustering for Customer Segmentation
This project implements KMeans Clustering on the Mall Customers dataset to identify distinct customer groups based on their shopping behavior. The goal is to segment customers using features like Age, Annual Income, and Spending Score.

📊 Project Overview
📁 Dataset: Mall_Customers.csv

🧠 Algorithm: KMeans Clustering (unsupervised learning)

⚙️ Steps:

Data Cleaning & Encoding

Feature Scaling (StandardScaler)

Optimal Clusters Selection (Silhouette Method)

KMeans Model Training

Cluster Visualization

📈 Sample Output
Silhouette Score Plot, elbow method , gap statistics to choose optimal K

Clustered scatter plot with color-coded segments

Centroid markers to indicate cluster centers


 How to Run
Clone this repo

Install required packages:

pip install pandas numpy matplotlib seaborn scikit-learn

save Mall_Customers.csv in the same notebook folder 

Open kmeans.ipynb in Jupyter

Run all cells and visualize the result

the result will be saved in groupedcustomers.csv




