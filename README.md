# 📊 Student Performance Analysis & Predictive Modeling

<div align="center">

![Project Banner](https://github.com/HesKal/Data-Analytics-Project/blob/main/assets/images/banner.png.jpg?raw=true)

*A complete data science project analyzing student performance and building predictive models to identify success factors.*

</div>


## 🌟 Project Overview

This repository contains a full-cycle data analytics project focused on analyzing student performance in mathematics, reading, and writing. Developed for the "Programming for Data Analytics" course, this project served as our introduction to version control with Git and GitHub, making it a foundational piece in my technical journey.

The goal was to move beyond simple analysis and apply a suite of machine learning techniques to understand the factors driving academic success and predict student outcomes. We explored everything from descriptive statistics and data visualization to regression, classification, and clustering.

---

## 🚀 The Data Science Lifecycle in Action

This project was structured to mirror a real-world data science workflow, covering four critical stages.

### 1. Exploratory Data Analysis (EDA )
Before building any models, we needed to deeply understand our data.
*   **Descriptive Statistics:** Wrote a custom Python function to generate a full statistical summary (mean, median, mode, variance, skew, etc.) for student scores.
*   **Data Sampling:** Implemented both random and systematic sampling techniques to create representative subsets of the data for analysis.
*   **Data Visualization:** Created a variety of plots to uncover patterns and relationships:
    *   **Histograms & Box Plots:** To understand the distribution of scores.
    *   **Scatter Plots:** To explore the relationship between different subjects (e.g., reading vs. writing scores).
    *   **Heatmaps:** To visualize the correlation between variables like gender, ethnicity, and academic performance.
*   **Hypothesis Testing:** Used Chi-Square and T-Tests to statistically validate our assumptions about the data.

### 2. Regression Modeling (Prediction)
We aimed to predict a student's math score based on their performance in other subjects.
*   **Simple Linear Regression:** Built a model to predict math scores using reading scores as a single predictor, achieving an **R² score of 68%**.
*   **Multiple Linear Regression:** Developed a more powerful model using both reading and writing scores, which dramatically improved predictive accuracy to an **R² score of 95.58%**.

### 3. Classification Modeling (Pass/Fail Prediction)
The goal here was to classify students as "Pass" or "Fail" based on their scores.
*   **Model Implementation:** Trained and evaluated four different classification algorithms:
    1.  Logistic Regression
    2.  K-Nearest Neighbors (KNN)
    3.  Naïve Bayes
    4.  Decision Tree
*   **Performance Evaluation:** Used Confusion Matrices, Accuracy, Precision, Recall, and F1-Scores to compare the models.
*   **Best-Fit Model:** **Logistic Regression** was identified as the best-fit model, demonstrating a strong balance of accuracy (94% on cross-validation) and reliability.

### 4. Clustering Analysis (Student Segmentation)
We used unsupervised learning to group students into distinct performance segments.
*   **K-Means Clustering:** Applied the Elbow Method to find the optimal number of clusters and grouped students into three segments: "Low Performers," "Moderate Performers," and "High Performers."
*   **Hierarchical Clustering:** Used dendrograms to visualize the nested structure of student groups.
*   **Actionable Strategy:** Developed a strategy based on these clusters to provide targeted interventions, such as extra support for the low-performing group and advanced challenges for the high-performing group.

---

## 🛠️ Technologies & Skills

*   **Languages & Libraries:** `Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`
*   **Data Science Concepts:**
    *   Data Preprocessing & Exploratory Data Analysis (EDA)
    *   Statistical Analysis & Hypothesis Testing
    *   Supervised Learning (Regression, Classification)
    *   Unsupervised Learning (Clustering)
    *   Model Evaluation & Selection (Confusion Matrix, R², Cross-Validation)
*   **Tools:** `Jupyter Notebook`, `Git`, `GitHub`

---

## 📂 Project Files

*   **`Project.ipynb`**: The main Jupyter Notebook containing all the Python code, analysis, and visualizations.
*   **`StudentsPerformance.csv`**: The raw dataset used for the analysis.
*   **`reports/`**: This folder contains the final project report (`.docx`) and presentation (`.pdf`).

---
## My Role and Contribution 
* 1- Define the purpose of data analysis for the chosen dataset
* 2- Identify and justify the type of programming used for data analysis
* 3- Identify the type and purpose of the machine learning algorithm to be implemented for the chosen dataset
* 4- Identify and justify the independent and dependent variables for the chosen dataset.
* 5- Justify why you want to perform the descriptive analysis for the chosen dataset. 
* 11- Perform the hypothesis test to find the correlation (Pearson and Spearman for numerical variable and chi-square test for categorical variable) between the independent variable and the dependent variable.
* 12- Assess the performance of the dependent variable to know whether the sample is representative of the normal population by a one-sample t-test.
* 15- Predict the value of the dependent variable from the different classifier such as Logistic Regression, KNN, Naïve-Bayes and Decision Tree.
* 19- Explain the strategy for improving the system after viewing the cluster diagram.

---
📄 Full Project Documentation
* Please refer to [View Student Preformance Report (PDF)](Student-Performance-Analysis-&-Predictive-Modeling-Report.docx/Student-Performance-Analysis-&-Predictive-Modeling-Report.pdf)

---
## 👥 The Team

This project was a successful collaboration between:


*   **Hessa Khalfan** ([@Heskal](https://github.com/Heskal ))
*   **Nourah Alghfeli** ([@NourahAlghfeli](https://github.com/NourahAlghfeli ))
*   **Maryam BinHamdah** ([@MaryamBinHamdah](https://github.com/MaryamBinHamdah ))
*   **Meera Mohamed**


Our teamwork was essential in tackling the diverse challenges of this project, from initial data exploration to the final model deployment.
