# MAIN-PROJECT-In-Python-with-POWER-BI-Breast-Cancer-at-Wisconsin-Diagnostic-
The main objective of this project is to analyze the Breast Cancer Wisconsin (Diagnostic) dataset using Python in Google Colab to identify patterns and characteristics that help distinguish between benign (non-cancerous) and malignant (cancerous) breast tumors.


# Breast Cancer Wisconsin (Diagnostic) Dataset Analysis using Python

## 📌 Project Overview

The **Breast Cancer Wisconsin (Diagnostic) Dataset Analysis** project focuses on analyzing breast tumor diagnostic measurements using Python in Google Colab. The project explores the characteristics of benign (non-cancerous) and malignant (cancerous) tumors through data cleaning, exploratory data analysis (EDA), data visualization, and machine learning classification.

The objective is to understand patterns in tumor features and evaluate how effectively machine learning models can distinguish between benign and malignant cases.

## 🎯 Objectives

- Load and understand the Breast Cancer Wisconsin (Diagnostic) dataset.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis to identify patterns and trends.
- Visualize relationships between diagnostic features.
- Identify important features that help distinguish benign and malignant tumors.
- Build and evaluate machine learning classification models.
- Interpret the results using appropriate evaluation metrics.

## 📂 Dataset Description

The Breast Cancer Wisconsin (Diagnostic) dataset contains measurements computed from digitized images of fine needle aspirates (FNA) of breast masses.

The dataset includes:

- **Diagnosis:** Benign (B) or Malignant (M).
- **Radius:** Mean distance from the center to points on the tumor perimeter.
- **Texture:** Variation in gray-scale intensity.
- **Perimeter:** Tumor boundary measurement.
- **Area:** Approximate tumor area.
- **Smoothness:** Variation in local radius lengths.
- **Compactness:** A measure related to perimeter and area.
- **Concavity:** Severity of concave portions of the tumor contour.
- **Concave points:** Number or extent of concave portions of the contour.
- **Symmetry:** Symmetry of the tumor shape.
- **Fractal dimension:** A measure of contour complexity.

The dataset includes 30 numerical diagnostic features and a diagnosis label. The commonly used Wisconsin Diagnostic dataset contains 569 observations.

**Dataset source:** [UCI Machine Learning Repository – Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

## 🛠️ Tools and Technologies

- **Python** – Programming language
- **Google Colab** – Cloud-based notebook environment
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine learning and model evaluation

## 🔍 Project Workflow

### 1. Data Loading
Import the dataset into Google Colab and load it into a Pandas DataFrame.

### 2. Data Understanding
Examine the dataset's shape, column names, data types, summary statistics, and diagnosis distribution.

### 3. Data Cleaning and Preprocessing
- Check for missing values and duplicate records.
- Remove unnecessary columns, such as an identifier column, where appropriate.
- Encode the diagnosis label into a numerical format if required.
- Scale numerical features when needed for the selected machine learning algorithms.

### 4. Exploratory Data Analysis (EDA)
Analyze the distribution of diagnostic measurements and compare feature patterns between benign and malignant tumors.

### 5. Data Visualization
Create visualizations such as:
- Diagnosis count plot
- Histograms of numerical features
- Correlation heatmap
- Box plots comparing tumor characteristics
- Scatter plots showing relationships between important features

### 6. Machine Learning
Split the data into training and testing sets and build suitable classification models, such as:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

### 7. Model Evaluation
Evaluate model performance using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

### 8. Conclusion
Summarize the major findings, identify useful diagnostic features, and compare the performance of the selected classification models.

## 📊 Expected Outcomes

- A clear understanding of the dataset and its diagnostic features.
- Identification of patterns that differentiate benign and malignant tumors.
- Visual insights into the relationships among tumor measurements.
- Comparison of machine learning classification models.
- Evaluation of classification performance using multiple metrics.
- A final summary of the analytical findings.

*Actual results and model performance should be reported after completing the analysis.*

## 💡 Key Learning Outcomes

Through this project, I aim to strengthen my skills in Python programming, data preprocessing, exploratory data analysis, data visualization, and machine learning classification. The project also provides practical experience in using Google Colab to perform an end-to-end data analysis workflow.

## 🚀 How to Run the Project

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Upload the downloaded dataset or load it directly from a trusted source.
4. Import the required Python libraries.
5. Execute the notebook cells in sequence.
6. Review the visualizations, model evaluation metrics, and final conclusions.

## ⚠️ Disclaimer

This project is intended for educational and analytical purposes only. The analysis and machine learning predictions are not intended to replace professional medical advice, clinical assessment, or diagnosis.

## 👩‍💻 Author

**Project:** Breast Cancer Wisconsin (Diagnostic) Dataset Analysis using Python in Google Colab

**Domain:** Data Analysis and Machine Learning

**Platform:** Google Colab
