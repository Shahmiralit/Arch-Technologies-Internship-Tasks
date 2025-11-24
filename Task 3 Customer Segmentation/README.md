
# 🎯 Project Objective

1. Analyze customer behavior

2. Preprocess and clean data

3. Apply KMeans clustering

4. Determine the optimal number of clusters using:

5. Elbow Method

6. Silhouette Score

7. Visualize clusters (PCA, boxplots)

8. Interpret customer segments

# 🧰 Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-Learn

Jupyter Notebook / Google Colab

# 📥 Dataset

The dataset contains customer attributes such as:

Age

Gender

Annual Income

Tenure

Number of Purchases

Average Purchase Value

Total Spending

Recency

Spending Score



# 🛠️ Steps Performed

1️⃣ Exploratory Data Analysis (EDA)

View dataset structure

Handle missing values

Summary statistics

Count categorical values

2️⃣ Data Preprocessing

Encode categorical variables (Label Encoding)

Feature scaling (StandardScaler)

Selecting numeric features for clustering

3️⃣ Determine Optimal Number of Clusters

Methods used:

Elbow Method (Inertia Plot)

Silhouette Score Analysis

The optimal k is chosen based on the best Silhouette Score.

4️⃣ Training K-Means Model

Fit KMeans on scaled features

Assign cluster labels to each customer

Append cluster labels to dataset

5️⃣ Cluster Interpretation

For each cluster:

Analyze average Income, Purchases, Total Spent, Recency, etc.

Identify meaningful customer segments such as:

High-Value Customers

Frequent Buyers

Low-Spending Customers

New Customers

6️⃣ Visualizations

PCA 2D Scatter Plot of clusters

Boxplots for key features across clusters

Cluster Center 
