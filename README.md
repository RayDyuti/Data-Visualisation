# 📊 Data Science Assignment – UDPLag Dataset Analysis

## 📌 Overview
This project is a complete data science workflow implemented in a Jupyter Notebook using Python. It covers all major stages of data analysis including data understanding, preprocessing, statistical analysis, and exploratory data analysis (EDA) on the UDPLag dataset.

The goal of this mini-project was to understand real-world data, clean and transform it, and extract meaningful insights using statistical and visualization techniques.

---

## 📂 Dataset
- Dataset Name: **UDPLag.csv**
- Source: CIC-DDoS2019 Dataset (Kaggle)
- Type: Network traffic dataset used for analyzing DDoS attack patterns

📌 Note: The dataset is included in this repository as a compressed (.zip) file due to its large size.

---

## ⚙️ Tools & Technologies Used
- Python
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - scipy

---

## 📑 Tasks Performed

### 🔹 Task 1: Data Understanding and Representation
- Explored dataset structure (shape, columns, data types)
- Computed statistical summaries (mean, median, variance, etc.)
- Created correlation matrix and heatmap
- Applied PCA for dimensionality reduction

---

### 🔹 Task 2: Descriptive and Inferential Statistics
- Calculated descriptive statistics
- Visualized distributions (histogram, density plot)
- Performed normality testing (Shapiro test)
- Conducted two-sample t-test
- Built a simple linear regression model

---

### 🔹 Task 3: Data Preprocessing
- Handled missing values and inconsistencies
- Removed duplicates
- Performed normalization (StandardScaler)
- Encoded categorical variables
- Reduced dimensionality using PCA
- Applied data discretization (binning)

---

### 🔹 Task 4: Exploratory Data Analysis (EDA)
- Created multiple visualizations:
  - Histogram
  - Boxplot
  - Scatter plot
  - Pair plot
  - Heatmap
- Identified patterns, correlations, and anomalies

---

### 🔹 Task 5: Reflection
- Documented learning outcomes
- Discussed challenges (large dataset, memory issues)
- Highlighted importance of preprocessing and efficiency

---

## ⚠️ Challenges Faced
- Handling a very large dataset
- Memory errors during one-hot encoding
- Slow visualizations due to high dimensionality
- Selecting meaningful features for statistical tests

Solutions included:
- Dropping high-cardinality columns
- Using sampling for visualization
- Reducing feature space for efficient computation

---

## 📊 Key Learnings
- Real-world data is messy and requires careful preprocessing
- Not all features are useful for analysis
- Efficiency is important when working with large datasets
- Statistical methods must be applied carefully with valid assumptions

---

## 🚀 How to Run
1. Extract the dataset zip file
2. Place `UDPLag.csv` in the same directory as the notebook
3. Open the notebook in Jupyter
4. Run cells sequentially

---

## 📌 Note
The notebook is provided in a clean format (without outputs).  
Run all cells to reproduce the results.

---

## 📎 File Structure
