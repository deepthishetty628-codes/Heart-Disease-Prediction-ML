# ❤️ Heart Disease Prediction using Machine Learning

## Overview

This project predicts the likelihood of heart disease using a Machine Learning classification model. It demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and model saving. The project was developed as part of an Artificial Intelligence Internship.

---

## Project Objective

The objective of this project is to build a machine learning model that predicts whether a person is likely to have heart disease based on various medical attributes. The project also focuses on data preprocessing, visualization, and model evaluation using standard machine learning techniques.

---

## Dataset

* **Dataset:** Heart Disease Dataset
* **Source:** Kaggle
* **Records:** 1025 (duplicates removed during preprocessing)
* **Target Variable:**

  * **0** = No Heart Disease
  * **1** = Heart Disease

---

## Technologies Used

* Python 3.x
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Project Workflow

1. Load the dataset
2. Data preprocessing

   * Remove duplicate records
   * Check missing values
3. Exploratory Data Analysis (EDA)

   * Histogram
   * Box Plot
   * Scatter Plot
   * Bar Chart
   * Correlation Heatmap
4. Split dataset into training and testing sets
5. Feature scaling using StandardScaler
6. Train Logistic Regression model
7. Evaluate model performance
8. Save the trained model

---

## Machine Learning Model

* **Algorithm:** Logistic Regression
* **Train-Test Split:** 80:20
* **Feature Scaling:** StandardScaler

---

## Model Evaluation

Evaluation metrics used:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score

### Result

* **Model Accuracy:** **80.33%**

---

## Project Files

```
Heart-Disease-Prediction-ML/
│
├── Heart_Disease_Prediction.ipynb
├── heart.csv
├── heart_cleaned.csv
├── heart_model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
└── screenshots/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/deepthishetty628-codes
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Open the Jupyter Notebook or Google Colab notebook:

Heart_Disease_Prediction.ipynb


Run all cells sequentially.



## Future Improvements

* Deploy the model using Flask or FastAPI
* Improve prediction accuracy using advanced machine learning algorithms
* Build a web-based user interface
* Add real-time prediction functionality


Author
RS DEEPTHI
B.Tech – Computer Science and Engineering (DevOps)

---

## License

This project is licensed under the MIT License.
