# California Housing Machine Learning Project

This project explores the **California Housing dataset** using several machine learning techniques.  
It was developed as a beginner ML project to cover regression, classification, and clustering tasks.

---

## 📊 Project Structure

### Part 1: Introduction & Setup
- Load California housing dataset (`fetch_california_housing`).
- Explore dataset (rows, features, target).
- Train/test split (80/20).

### Part 2: Regression Task
- Baseline **Linear Regression**.
- Compare with **Ridge** and **Lasso** regressions.
- Add polynomial features for `MedInc` and `HouseAge`.
- Evaluate with RMSE, MAE, R².
- Identify strongest features.

### Part 3: Classification Task
- Binary classification: Expensive vs. Affordable houses.
- Models: **Logistic Regression** and **Decision Tree**.
- Multi-class classification by quartiles using **Random Forest**.
- Evaluation: Accuracy, Precision, Recall, F1, Confusion Matrix.

### Part 4: Clustering Task
- Standardize features and apply **PCA (2D)**.
- Cluster with **KMeans (k=3,4,5)**.
- Evaluate inertia and silhouette score.
- Visualize clusters in PCA space and on California map.
- Discuss geographic alignment of clusters.

### Part 5: Comparative Analysis
- Summarize results of regression, classification, clustering.
- Compare supervised vs unsupervised learning.
- Highlight 3 key takeaways.

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/california-housing-ml.git
cd california-housing-ml
pip install -r requirements.txt
