
Lab 4

## 📌 Aim
To perform **Data Visualization** using Python libraries on the Iris dataset and explore the relationship between different flower features.

---

## 📊 Dataset
- Dataset: **Iris Flower Dataset** (from `sklearn.datasets`)
- Shape: **150 rows × 5 columns**
- Features:
  1. Sepal length (cm)
  2. Sepal width (cm)
  3. Petal length (cm)
  4. Petal width (cm)
- Target (Class): **Species**
  - Setosa  
  - Versicolor  
  - Virginica  

---

## 🛠️ Libraries Used
- `pandas` → for data handling  
- `matplotlib` → for visualization (plots, histograms, heatmaps)  
- `seaborn` → for advanced & beautiful plots  
- `sklearn.datasets` → to load Iris dataset  

---

## 🧾 Steps Performed

## 1. Load the Dataset
- Imported Iris dataset from `sklearn.datasets`
- Converted into Pandas DataFrame with column names

## 2. Univariate Visualization
- Histograms for each feature (Sepal Length, Sepal Width, Petal Length, Petal Width)
- Added colors, axis labels, and titles
- Used **KDE curves** for smooth distributions

## 3. Bivariate Visualization
- Scatter plot: Sepal length vs Sepal width (color-coded by species)
- Scatter plot: Petal length vs Petal width (color-coded by species)

## 4. Category-based Visualization
- Boxplot of Petal Length grouped by Species
- Violin-style plot (Boxplot + Scatter overlay)

## 5. Correlation Visualization
- Computed correlation matrix of features
- Visualized using a **heatmap**

---

## 📷 Sample Outputs
- Histograms of features  
- Scatter plots for feature relationships  
- Boxplots for category-based comparison  
- Heatmap for correlations  

---

## 🚀 How to Run
1. Open the Jupyter Notebook (`Lab4_Iris_Visualization.ipynb`) in **Google Colab** or Jupyter.  
2. Run all cells step by step.  
3. Visualizations will appear inline.  

---

## 📝 Author
- Your Name (Replace this with your name)
- Lab Assignment 4 (Data Visualization using Python)

