# ❤️ Heart Failure Prediction Using Machine Learning

A Machine Learning project that analyzes clinical patient data to predict the likelihood of a death event among heart failure patients. This project applies supervised learning techniques to identify patterns in medical records and evaluate classification performance.

---

## 📌 Project Overview

Heart failure is a serious cardiovascular condition that requires careful monitoring and timely medical attention.

This project uses machine learning algorithms to analyze clinical records of heart failure patients. It focuses on identifying patterns in patient health indicators and predicting the likelihood of a **death event** based on the available clinical features.

The project also explores medical attributes and evaluates machine learning models for classification.

## 🎯 Project Objectives

- Analyze clinical data of heart failure patients.
- Predict death events using machine learning.
- Explore important medical features.
- Compare classification algorithms.
- Evaluate model performance.
- Identify the best-performing model.

## 📂 Dataset

The dataset contains clinical records of heart failure patients.

**Dataset Features**

| Feature | Description |
|---|---|
| Age | Age of the patient |
| Anaemia | Whether the patient has anaemia |
| Creatinine Phosphokinase | Level of CPK enzyme in the blood |
| Diabetes | Whether the patient has diabetes |
| Ejection Fraction | Percentage of blood leaving the heart |
| High Blood Pressure | Whether the patient has high blood pressure |
| Platelets | Platelet count |
| Serum Creatinine | Serum creatinine level |
| Serum Sodium | Serum sodium level |
| Sex | Patient's sex |
| Smoking | Whether the patient smokes |
| Time | Follow-up period |

**Target Variable: Death Event**

| Value | Meaning |
|---|---|
| `0` | Patient Survived |
| `1` | Death Event |

*Note: The target variable represents the recorded death event during the study period. It should not be interpreted as a direct diagnosis of heart failure.*

## 🛠️ Technologies & Libraries

- **Python** – Core programming language
- **Jupyter Notebook** – Model development and experimentation
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine learning algorithms and evaluation

## 🤖 Machine Learning Workflow

The project follows these steps:

1. Import Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Prediction

## ⚙️ Project Workflow

```text
Clinical Dataset
       |
       v
Data Cleaning
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
Death Event Prediction
```

## 📊 Model Output

The Jupyter Notebook trains and evaluates machine learning classification models using clinical patient data.

Model performance is assessed through classification metrics such as:

- Accuracy
- Prediction results

*Note: Specific model accuracy values and the best-performing algorithm have not been included because they were not provided in the project information.*

## 📁 Project Structure

```text
Heart-Failure-Prediction/
│
├── heart failure.csv
├── Heart failure detection problem.ipynb
├── README.md
└── requirements.txt
```

## 🚀 Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/anasmurtaza/Heart-Failure-Prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd Heart-Failure-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the following notebook:

`Heart failure detection problem.ipynb`

Run the notebook cells to explore the dataset, train machine learning models, and view prediction results.

## 🔮 Future Improvements

- Hyperparameter tuning for better model performance.
- Feature engineering and selection.
- Develop an interactive Streamlit web application.
- Build a Flask API for model integration.
- Apply SHAP or LIME for model explainability.
- Deploy the application to a cloud platform.

## 👨‍💻 Author

**Muhammad Anas Murtaza**

- GitHub: [anasmurtaza](https://github.com/anasmurtaza)
- LinkedIn: [Muhammad Anas Murtaza](https://www.linkedin.com/in/m-anas-murtaza)

**Interests:** Machine Learning | Data Science | Artificial Intelligence

---

⭐ If you find this project useful, consider giving it a star on GitHub!

**Disclaimer:** This project is developed for educational and research purposes only. Its predictions are not a substitute for professional medical advice, diagnosis, or treatment.
