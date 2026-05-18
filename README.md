# 💳 Credit Card Customer Segmentation using K-Means
## ARTI 308: Machine Learning - Lab 11

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Overview
This assignment applies Unsupervised Machine Learning techniques to segment credit card customers based on their purchasing behavior. By clustering customers into distinct groups, businesses can design targeted marketing strategies and optimize financial services.

### Key Steps Completed
1. **Data Preprocessing:** Handled missing values using mean imputation and standardized numerical features using `StandardScaler` to ensure uniform distance calculations.
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and correlation matrices to understand customer behavior metrics.
3. **Determining Optimal K:** Evaluated cluster counts using both the **Elbow Method (Inertia)** and the **Silhouette Score**, identifying `K=4` as the optimal number of clusters.
4. **K-Means Clustering:** Segmented customers into four distinct profiles (Everyday Shoppers, Cash Advance Users, Low Activity, and Premium/High-Value).
5. **Dimensionality Reduction:** Used **PCA (Principal Component Analysis)** to reduce data dimensionality and visualize the clusters in a 2D space.

### Files
* `Credit Card Customer Segmentation Assignment.ipynb`: Full implementation, clustering models, and business strategy answers.
* `CC_GENERAL.csv`: The dataset containing credit card usage metrics.
