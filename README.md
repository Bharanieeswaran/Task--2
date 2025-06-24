# 📊 Task 2: Exploratory Data Analysis (EDA)

## 📌 Objective
To understand the structure, patterns, trends, and anomalies in the dataset using statistical summaries and visualizations.

---

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (optional for interactive plots)

---

## 📁 Dataset
**Titanic Dataset**  
Includes features such as Passenger ID, Name, Age, Gender, Pclass, Fare, and Survival status.

---

## 🔍 Steps Performed

1. **Loaded and Explored the Dataset**
   - Used `df.head()`, `df.info()`, and `df.describe()` to understand data types and summary statistics.

2. **Generated Summary Statistics**
   - Calculated mean, median, mode, standard deviation, and interquartile ranges.

3. **Univariate Analysis**
   - Plotted **histograms**, **boxplots**, and **count plots** for numeric and categorical features.

4. **Bivariate and Multivariate Analysis**
   - Used **pairplots** and **correlation heatmaps** to analyze relationships between features.
   - Analyzed survival rate across gender, class, and age groups.

5. **Identified Patterns and Anomalies**
   - Detected skewed distributions using histograms.
   - Found outliers via boxplots.
   - Observed high correlation between Pclass and Fare.

---

## 💡 Key Insights
- Most passengers were in class 3, and survival rate was higher in class 1.
- Females had a significantly higher survival rate than males.
- Age was slightly right-skewed, with a few older outliers.
- Fare showed heavy skewness and multiple outliers.

---

## 📈 Visualizations Used
- Histograms for distribution
- Boxplots for outlier detection
- Countplots for categorical analysis
- Pairplots to explore relationships
- Heatmaps to show correlation between numeric features

---

## ❓ Interview Questions Answered

1. **What is the purpose of EDA?**  
   To gain insights, detect anomalies, and prepare data for modeling.

2. **How do boxplots help?**  
   They show median, quartiles, and outliers in numerical data.

3. **What is correlation and why is it useful?**  
   It measures the linear relationship between variables; helps identify multicollinearity.

4. **How to detect skewness?**  
   Via histograms or calculating skewness value (`df.skew()`).

5. **What is multicollinearity?**  
   When two or more independent variables are highly correlated, affecting model performance.

6. **Tools for EDA?**  
   Pandas, Seaborn, Matplotlib, Plotly

7. **Time when EDA helped find a problem?**  
   (Add your experience or mention discovering outliers/missing values or wrong data types.)

8. **Role of visualization in ML?**  
   Helps in understanding data patterns, feature importance, and model interpretability.

---
