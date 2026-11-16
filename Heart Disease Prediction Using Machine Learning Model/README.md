# ❤️ Heart Disease Prediction Using Machine Learning

A machine learning project that predicts the likelihood of heart disease using patient health data. This project explores and compares multiple supervised learning algorithms to identify the best-performing classification model.

## 📌 Project Overview

Heart disease is a major global health concern. Early risk prediction can support further medical assessment and help healthcare professionals make informed decisions.

This project applies machine learning classification algorithms to patient health attributes, including age, chest pain type, resting blood pressure, cholesterol, maximum heart rate, and other clinical indicators.

The goal is to compare different models and identify which performs best on the dataset.

## 🎯 Project Objectives

- Predict the likelihood of heart disease using machine learning.
- Explore and preprocess patient health data.
- Perform exploratory data analysis (EDA).
- Train and compare multiple classification algorithms.
- Evaluate model performance using accuracy.
- Identify the best-performing model.

## 📂 Dataset

The dataset contains patient health information and a target variable indicating the presence or absence of heart disease.

**Target Variable**

| Value | Meaning |
|---|---|
| `0` | No Heart Disease |
| `1` | Heart Disease |

**Dataset Features**

| Feature | Description |
|---|---|
| Age | Patient's age |
| Sex | Patient's sex |
| Chest Pain Type | Type of chest pain |
| Resting Blood Pressure | Blood pressure at rest |
| Cholesterol | Serum cholesterol level |
| Fasting Blood Sugar | Fasting blood sugar indicator |
| Resting ECG | Resting electrocardiographic results |
| Maximum Heart Rate | Maximum heart rate achieved |
| Exercise Induced Angina | Angina caused by exercise |
| ST Depression | ST depression induced by exercise |
| Slope | Slope of the peak exercise ST segment |
| Number of Major Vessels | Number of major vessels |
| Thalassemia | Thalassemia test result |

**Dataset file:** `heart.csv`

## 🛠️ Technologies & Libraries

- **Python** – Core programming language
- **Jupyter Notebook** – Model development and experimentation
- **NumPy** – Numerical computations
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine learning algorithms and evaluation

## 🤖 Machine Learning Algorithms

The following supervised classification algorithms are included:

1. Logistic Regression
2. Naive Bayes
3. Decision Tree
4. Random Forest
5. Support Vector Machine (SVM)
6. K-Nearest Neighbors (KNN)

## ⚙️ Project Workflow

```text
Dataset Collection
       |
       v
Data Preprocessing
       |
       v
Exploratory Data Analysis
       |
       v
Feature Selection
       |
       v
Train-Test Split
       |
       v
Model Training
       |
       v
Model Evaluation
       |
       v
Heart Disease Prediction
```

## 📊 Model Performance

The following accuracy results are reported in this project:

| Algorithm | Accuracy |
|---|---:|
| Logistic Regression | 85% |
| Naive Bayes | 85% |
| Decision Tree | 81% |
| Random Forest | 90%+ |

**Best-performing model:** Random Forest

*Note: The results shown are the reported project results. Actual performance may vary depending on the dataset split and evaluation setup.*

## 📁 Project Structure

```text
ML-Heart-Disease-Prediction/
│
├── heart.csv
├── Heart Disease Prediction Using Machine Learning Model.ipynb
├── README.md
└── requirements.txt
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/anasmurtaza/ML-Heart-Disease-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd ML-Heart-Disease-Prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

`Heart Disease Prediction Using Machine Learning Model.ipynb`

Run the notebook cells to explore the dataset, train the models, and review the results.

## 🔮 Future Improvements

- Develop an interactive web application using Streamlit or Flask.
- Apply hyperparameter tuning to improve model performance.
- Perform additional feature engineering.
- Add more evaluation metrics, such as precision, recall, F1-score, and ROC-AUC.
- Deploy the application to a cloud platform.

## 👨‍💻 Author

**Muhammad Anas Murtaza**

- GitHub: [anasmurtaza](https://github.com/anasmurtaza)
- LinkedIn: [Muhammad Anas Murtaza](https://www.linkedin.com/in/m-anas-murtaza/)

**Interests:** Machine Learning | Data Science | Artificial Intelligence

---

⭐ If you find this project useful, consider giving it a star!

**Disclaimer:** This project is developed for educational and research purposes only. Its predictions are not a substitute for professional medical advice, diagnosis, or treatment.
