# 🛍️ Customer Segmentation with K-Means Clustering

This project uses **unsupervised machine learning** to segment customers based on their **Annual Income** and **Spending Score**. By identifying customer clusters, businesses can tailor marketing strategies and improve customer satisfaction.

---

## 📂 Dataset

- **Source**: [Mall Customer Segmentation Data – Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)
- **Features Used**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🔍 Objectives

- Explore and clean the dataset
- Scale numerical features
- Visualize customer behavior
- Apply **K-Means Clustering**
- Determine the optimal number of clusters using the **Elbow Method**
- Visualize and analyze customer segments

---

## ⚙️ Preprocessing Steps

- Checked for null values (✅ No missing data)
- Applied `MinMaxScaler` to normalize:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`
- Suppressed unnecessary warnings for clean output

---

## 📈 Visual Explorations

- Distribution plots for income and spending
- 2D scatter plots showing cluster separation
- Cluster centroids marked on K-Means results

---

## 📊 Clustering Approach

- Used `KMeans` from `sklearn.cluster`
- Determined optimal number of clusters:
  - Applied the **Elbow Method**
  - Opted for **K = 5**, balancing clustering precision and computational efficiency
- Analyzed and labeled clusters

---

## 🧠 Results Summary

- **5 unique customer segments** were identified
- Each group exhibits different income and spending behaviors
- Helps businesses make data-driven decisions for targeted marketing

---

## 💡 Future Enhancements

> *These steps are not implemented in this notebook but are suggested for deeper analysis:*

- Try **DBSCAN** or **Hierarchical Clustering**
- Incorporate demographic features like `Age` and `Gender`
- Build an interactive dashboard using **Plotly**, **Dash**, or **Streamlit**
- Perform **spending analysis per cluster**

---

## 📎 Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 📘 License

This project is licensed for educational and personal use.

---

## 🙋‍♀️ Author

**Alaa Mohamed**  
Computer Engineer | Data & AI Enthusiast

---

