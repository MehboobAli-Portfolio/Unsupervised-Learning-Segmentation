# Unsupervised Learning Segmentation 🔍

A specialized repository focused on Unsupervised Machine Learning techniques. This hub demonstrates the ability to discover hidden structures and patterns within unlabeled data, specifically utilizing centroid-based clustering to segment complex datasets.

## 🚀 Overview
As a Software Engineer, I developed this project to showcase the implementation of the **K-Means Clustering** algorithm. Unlike supervised learning, this approach finds natural groupings within data without pre-defined labels, making it essential for behavioral analysis and data-driven discovery.

## 📁 Repository Structure
The project is contained within a dedicated directory including the Jupyter Notebook and the behavioral dataset.

* **01_KMeans_Customer_Segmentation:** Grouping customers based on demographic and financial attributes (Age, Education, Income, Debt).

---

## 🛠️ Technical Deep-Dive

### 1. K-Means Clustering - Behavioral Analysis 👤
* **Objective:** Segment a customer base into distinct groups to identify unique usage and financial profiles.
* **Algorithm Logic:** Utilized the `KMeans` implementation from Scikit-Learn to partition 'n' observations into 'k' clusters where each observation belongs to the cluster with the nearest mean (centroid).
* **Feature Engineering:** Implemented data normalization using `StandardScaler` to ensure that distance-based calculations were not biased by varying feature scales.
* **Visualization:** Developed **3D Scatter Plots** using `Axes3D` to visualize the relationship between multiple variables (Education, Age, and Income) and their respective cluster assignments.

---

## 💻 Tech Stack
* **Language:** Python 3.13+
* **Core Libraries:** Scikit-Learn, NumPy, Pandas
* **Visualization:** Matplotlib (including `mpl_toolkits.mplot3d`), Seaborn
* **Environment:** Jupyter Notebooks

## ⚙️ Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Unsupervised-Learning-Segmentation.git](https://github.com/YOUR_USERNAME/Unsupervised-Learning-Segmentation.git)
