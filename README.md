# Gaussian Mixture Model (GMM) Clustering on Wine Dataset

## 📌 Project Overview

This project demonstrates **unsupervised machine learning** using the **Gaussian Mixture Model (GMM)** algorithm to cluster wine samples based on their chemical properties. The model identifies groups of wines with **high** and **low alcohol content** without using predefined class labels.

The project also applies **Principal Component Analysis (PCA)** to visualize the clusters in two dimensions and evaluates clustering quality using the **Silhouette Score**.

---

## 🚀 Features

* Data preprocessing and normalization using **MinMaxScaler**
* Clustering using **Gaussian Mixture Model (GMM)**
* Automatic identification of **High Alcohol** and **Low Alcohol** clusters
* Cluster quality evaluation using **Silhouette Score**
* Dimensionality reduction with **PCA**
* Visualization of clustered wine samples
* Analysis of the most influential features contributing to principal components

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

The project uses the **Wine Dataset**, a well-known machine learning benchmark dataset.

It contains:

* **178 wine samples**
* **13 chemical attributes**
* Samples collected from **3 different wine cultivars**

Some important features include:

* Alcohol
* Malic Acid
* Ash
* Alcalinity of Ash
* Magnesium
* Total Phenols
* Flavanoids
* Color Intensity
* Hue
* Proline

---

## 📊 Workflow

1. Load the Wine dataset
2. Remove non-numeric columns (if present)
3. Normalize the features using MinMaxScaler
4. Train a Gaussian Mixture Model with two clusters
5. Predict cluster assignments
6. Identify clusters as High Alcohol or Low Alcohol
7. Evaluate clustering using Silhouette Score
8. Apply PCA for dimensionality reduction
9. Visualize the clusters

---

## 📈 Results

The project produces:

* Gaussian Mixture clusters
* High Alcohol vs Low Alcohol classification
* Silhouette Score for clustering performance
* PCA visualization of clustered wines
* Top contributing features for each principal component

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/RajdeepT/Wine_Clustering_Using_GMM.git
```

Move into the project directory:

```bash
cd Wine_Clustering_Using_GMM
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Running the Project

Launch the notebook:

```bash
jupyter notebook DSA_Project_GMM.ipynb
```

or open it directly in **Google Colab**.

---

## 📁 Project Structure

```
├── DSA_Project_GMM
├── README.md
├── wine_custering.csv
```

---

## 📚 Machine Learning Concepts Covered

* Unsupervised Learning
* Gaussian Mixture Models (GMM)
* Clustering
* Data Normalization
* Principal Component Analysis (PCA)
* Silhouette Score
* Data Visualization

---

## 🎯 Future Improvements

* Compare GMM with K-Means, DBSCAN, and Hierarchical Clustering
* Determine the optimal number of clusters using BIC/AIC
* Add interactive visualizations with Plotly
* Perform deeper feature importance analysis

---

## 👨‍💻 Author

**Rajdeep Thakur**

B.Tech in Information Technology
Machine Learning & Data Analytics Enthusiast

---

## 📜 License

This project is intended for **educational and learning purposes**.
