# KMeans Customer Segmentation

## 📌 Project Overview
This project implements **customer segmentation using the KMeans clustering algorithm**.  
The objective is to group customers based on their **annual income** and **spending behavior**, helping businesses better understand customer patterns and target them effectively.

---

## 🛠 Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📂 Dataset
**Mall Customer Segmentation Dataset**

Features used in this project:
- Annual Income (k$)
- Spending Score (1–100)

The `CustomerID` and categorical columns were excluded as they do not contribute to distance-based clustering.

---

## 🔍 Methodology
1. Loaded and explored the dataset
2. Selected relevant numerical features
3. Applied feature scaling using `StandardScaler`
4. Used the **Elbow Method** to determine the optimal number of clusters
5. Trained the KMeans model
6. Assigned cluster labels to customers
7. Visualized customer segments using scatter plots
8. Saved the segmented dataset as a CSV file

---

## 📊 Results
- Optimal number of clusters identified using the Elbow Method
- Customers grouped into **5 distinct clusters**
- Clear visual separation of customer segments based on income and spending behavior

---

## 🧠 Customer Segments
| Cluster | Description |
|-------|------------|
| 0 | High Income – High Spending |
| 1 | Low Income – Low Spending |
| 2 | High Income – Low Spending |
| 3 | Low Income – High Spending |
| 4 | Average Income – Average Spending |

---

## 📁 Project Files
- `KMeans_Customer_Segmentation.ipynb` – Jupyter Notebook implementation
- `mall_customers.csv` – Original dataset
- `segmented_customers.csv` – Dataset with cluster labels
- `README.md` – Project documentation

---

## 🎯 Conclusion
This project demonstrates the application of **unsupervised learning** to segment customers into meaningful groups.  
Such segmentation can support data-driven decisions in marketing, customer relationship management, and business strategy.
