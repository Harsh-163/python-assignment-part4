# 🎓 Student Performance: Analysis & Predictive Modeling (Part 4)


This module focuses on **Exploratory Data Analysis (EDA)**, **Statistical Visualization**, and **Supervised Machine Learning** using a synthetic student dataset. It demonstrates the transition from raw data to actionable predictive insights.

---

## 🚀 Key Objectives

### 1. Data Manipulation (Pandas)
* **Dataset Management:** Automated generation and loading of `students.csv`.
* **Descriptive Statistics:** Comprehensive analysis of class means, standard deviations, and score distributions.
* **Data Segmentation:** Using boolean indexing to compare performance metrics between "Passing" and "Failing" groups.
* **Feature Engineering:** Creating calculated columns like `avg_score` and `overall_avg` for deeper student profiling.

### 2. Data Visualization (Matplotlib & Seaborn)
* **Distribution Analysis:** Histograms with mean-line overlays to visualize grade density.
* **Correlation Studies:** Scatter plots identifying the relationship between study habits and academic outcomes.
* **Variance Tracking:** Side-by-side Box plots to analyze how attendance consistency differentiates successful students.
* **Statistical Regression:** Leveraging Seaborn's `regplot` to mathematically visualize the trend between attendance and final scores.

### 3. Machine Learning (Scikit-Learn)
* **Preprocessing Pipeline:** Implementation of `StandardScaler` to normalize features (Mean=0, Std=1), ensuring unbiased model training.
* **Model Architecture:** Training a **Logistic Regression** classifier to predict student outcomes.
* **Performance Evaluation:** Calculating accuracy scores and analyzing individual test-set predictions.
* **Interpretability:** Extracting and visualizing model coefficients to identify the "Impact Factors" (Feature Importance) of student success.

---

## 📈 Project Insights
* **The Attendance Factor:** Visual analysis confirms that passing students maintain a significantly higher and more stable attendance percentage.
* **Predictive Drivers:** The Machine Learning model identifies `study_hours_per_day` and `attendance_pct` as the strongest positive predictors for a "Pass" classification.
* **Scalability:** The pipeline is designed with modularity, allowing it to be applied to larger, real-world educational datasets with minimal adjustments.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Handling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Model Selection, Preprocessing, Linear Models)

---

## 👤 Author
**Harshwardhan Srivastava** 
*Bitsom Assignment*
