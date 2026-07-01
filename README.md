# Iris-Classification-ML-
Machine Learning classification project using the Iris dataset with Logistic Regression, KNN, and Random Forest. Includes preprocessing, model evaluation, confusion matrix, and performance comparison.

# 🌸 Iris Flower Classification Using Machine Learning

## 📌 Project Overview

This project was completed as part of the **Pluto Academy AI & Machine Learning Internship Program (Project 2)**. The objective is to build, train, evaluate, and compare multiple machine learning models to classify Iris flower species based on their physical characteristics.

---

## 🎯 Objective

The main objectives of this project are to:

- Load and inspect the Iris dataset.
- Perform data preprocessing and cleaning.
- Apply feature engineering techniques.
- Train multiple machine learning classification models.
- Compare model performance using evaluation metrics.
- Select the best-performing model and justify the selection.

---

## 📂 Dataset Information

**Dataset Name:** Iris Flower Classification Dataset

**Source:** Kaggle

**Dataset File:** `Iris.csv`

### Features

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

### Target Variable

- Species

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Machine Learning Workflow

### 1. Data Loading
- Imported the Iris dataset into Google Colab.
- Displayed the dataset structure and sample records.

### 2. Data Inspection
- Checked dataset dimensions.
- Verified data types.
- Identified missing values.
- Detected duplicate records.
- Reviewed statistical summary.

### 3. Data Preprocessing
- Removed the unnecessary `Id` column.
- Removed duplicate records.
- Verified missing values.
- Encoded the target variable using Label Encoding.

### 4. Feature Engineering
- Selected input features (X).
- Selected target variable (y).
- Analyzed feature relationships using a correlation heatmap.

### 5. Train-Test Split
- Training Data: 80%
- Testing Data: 20%

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

---

## 📊 Model Evaluation

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

A comparison table was generated to identify the best-performing model.

---

## 📉 Confusion Matrix

A confusion matrix was created for the best-performing model to visualize prediction accuracy and classification errors.

---

## 🏆 Best Model

Based on the evaluation metrics, the **Random Forest Classifier** achieved the best overall performance for the Iris classification task.

---

## 📁 Repository Structure

```
Iris-Classification-ML/
│
├── README.md
├── Iris_Classification.ipynb
├── Iris.csv
├── Model_Comparison_Table.csv
└── .gitignore
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Iris_Classification.ipynb` using Google Colab or Jupyter Notebook.
3. Upload the `Iris.csv` dataset if required.
4. Run all notebook cells sequentially.
5. Review the evaluation metrics, comparison table, and confusion matrix.

---

## 📚 Learning Outcomes

Through this project, I learned how to:

- Perform data preprocessing.
- Encode categorical variables.
- Split datasets into training and testing sets.
- Train multiple machine learning models.
- Evaluate model performance using standard metrics.
- Compare algorithms and select the best-performing model.
- Visualize results using a confusion matrix.

---

## 👨‍💻 Author

**Mugundhan R**

Bachelor of Engineering (Computer Science and Engineering)

AI & Machine Learning Intern – Pluto Academy

**GitHub:** *(Add your GitHub Profile URL)*

**LinkedIn:** *(Add your LinkedIn Profile URL)*

---

## 🙏 Acknowledgements

- Pluto Academy AI & Machine Learning Internship Program
- Kaggle for providing the Iris dataset
- Scikit-learn for machine learning tools
- Python open-source community
