# PRODIGY_ML_02

# 🛍️ Customer Segmentation with K-Means Clustering

This project applies unsupervised machine learning (K-Means clustering) to segment customers based on their **annual income** and **spending score**, using the `Mall_Customers.csv` dataset.

---

## 📊 Objective

To identify distinct groups of customers to help businesses target marketing efforts more effectively using clustering techniques.

---

## 🧠 Techniques Used

- **StandardScaler** – For feature scaling  
- **KMeans Clustering** – To segment customers  
- **Elbow Method** – To find optimal `k` (number of clusters)  
- **Seaborn/Matplotlib** – For visualization

---

## 📂 Dataset

- **Source:** `Mall_Customers.csv`
- **Features Used:**
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 📈 Elbow Method

Used to determine the optimal number of clusters (`k`) by plotting the **Within-Cluster Sum of Squares (WCSS)**:

![Elbow Curve](images/elbow.png)

---

## 🎯 Cluster Visualization

Once the optimal `k` is chosen (e.g., `k = 5`), the data is clustered and visualized as shown:

![Clusters](images/clusters.png)

---

## 🚀 How to Run

1. Clone this repo
   ```bash
   git clone https://github.com/Faham1111/PRODIGY_ML_01.git
   cd PRODIGY_ML_01
