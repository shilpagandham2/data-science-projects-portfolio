# Customer Segmentation using Clustering

## 📌 Overview
This project applies clustering techniques to segment customers based on survey data. The goal is to identify patterns and group similar customers together for better business insights.

---

## 📊 Dataset
- File: `autoSurvey.csv`
- Records: 793 rows × 12 features
- Features include:
  - driving_properties
  - interior
  - technology
  - comfort
  - reliability
  - handling
  - power
  - consumption
  - sporty
  - safety

---

## ⚙️ Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Plotly
- Scikit-learn
- SciPy

---

## 🔍 Steps Performed

### 1. Data Loading
- Loaded dataset using pandas
- Explored structure and dimensions

### 2. Covariance Analysis
- Computed covariance matrix to understand relationships between variables

### 3. Hierarchical Clustering
- Used `scipy` and `plotly.figure_factory`
- Generated dendrogram to visualize clusters

### 4. Heatmap Visualization
- Created heatmap using Plotly
- Combined with dendrogram for better cluster interpretation

---

## 📈 Key Visualizations

### Dendrogram
- Shows hierarchical grouping of customers
- Helps determine number of clusters

### Heatmap
- Displays similarity between customers
- Combined with clustering for insights

---

## 🎯 Insights
- Customers can be grouped based on preferences like comfort, performance, and technology
- Clustering helps identify similar behavior patterns
- Useful for targeted marketing and personalization

---

## 🚀 How to Run
1. Open the notebook `assignment.ipynb`
2. Ensure required libraries are installed
3. Run all cells

---

## 📁 Files Included
- `assignment.ipynb`
- `autoSurvey.csv`

---

## 💡 Future Improvements
- Apply K-Means clustering for comparison
- Use PCA for dimensionality reduction
- Add cluster labeling and interpretation
