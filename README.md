# DevelopersHub-Internship-Tasks
Data Science &amp; Analytics Internship Tasks - DevelopersHub Corporation
 Task 1: Exploring and Visualizing the Iris Dataset

**DevelopersHub Corporation — Data Science & Analytics Internship**

---

## 📌 Task Objective

Understand how to read, summarize, and visualize a dataset using Python.  
The goal is to explore the classic **Iris Dataset** through data inspection and multiple visualizations.

---

## 📂 Dataset

- **Name:** Iris Dataset
- **Source:** Loaded directly via `seaborn` library (no download needed)
- **Size:** 150 rows × 5 columns
- **Features:**
  - `sepal_length` — Sepal length in cm
  - `sepal_width` — Sepal width in cm
  - `petal_length` — Petal length in cm
  - `petal_width` — Petal width in cm
  - `species` — Target: Setosa, Versicolor, Virginica

---

## 🛠️ My Approach

### Step 1 — Data Loading & Inspection
- Loaded dataset using `seaborn.load_dataset('iris')`
- Inspected using `.shape`, `.columns`, `.head()`, `.info()`, `.describe()`
- Checked for missing values → None found ✅

### Step 2 — Visualizations
| Plot | Purpose |
|------|---------|
| Scatter Plot (Sepal) | Relationship between sepal length & width |
| Scatter Plot (Petal) | Relationship between petal length & width |
| Pairplot | All feature combinations at once |
| Histogram (all features) | Distribution of each feature |
| Histogram (by species) | Distribution comparison across species |
| Box Plot (by species) | Spread, median, and outliers per species |
| Correlation Heatmap | Correlation strength between all features |

---

## 📊 Results & Key Insights

1. **Dataset is clean** — No missing values
2.  **Setosa** is clearly separable from other species using petal dimensions
3.  **Petal length & petal width** are highly correlated (r = 0.96)
4.  **Box plots** show Virginica has the largest petal size
5.  **Bimodal distribution** in petal features confirms distinct species grouping
6.  Sepal width has **weak/negative correlation** with other features

---

## 🧰 Libraries Used

```python
pandas
matplotlib
seaborn
```

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `Task1_Iris_Visualization.ipynb` file
3. Click **Runtime → Run All**
4. No dataset download needed — loads automatically!

---

## 📁 File Structure

```
Task1-Iris-Visualization/
│
├── Task1_Iris_Visualization.ipynb   ← Main Jupyter Notebook
└── README.md                        ← This file
```

---

*Submitted by: Anisha Maroof | DevelopersHub Corporation Internship 2026*

