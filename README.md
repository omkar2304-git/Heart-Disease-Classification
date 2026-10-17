# ❤️ Heart Disease Classification

A machine learning project that uses patient clinical attributes to classify whether a patient is likely to have heart disease.

> ⚠️ Created for learning purposes only. This project is not intended for medical diagnosis.

## 📌 Project Overview

The goal of this project is to explore a heart disease dataset, perform exploratory data analysis (EDA), train multiple classification models, and compare their performance.

## 🛠️ Technologies Used

Python · Pandas · NumPy · Matplotlib · Seaborn · scikit-learn · Jupyter Notebook

## 📊 Dataset

- **Size:** 109 patient records
- **Source:** [** Heart disease dataset provided in a machine learning bootcamp ]
- **Features:** Age, Sex, Chest Pain, Resting Blood Pressure, Cholesterol, Maximum Heart Rate, Exercise-Induced Angina, Oldpeak
- **Target:** Heart Disease (present or not)

## 🔍 Exploratory Data Analysis

- Dataset structure and target distribution
- Age distribution
- Heart disease frequency
- Chest pain categories
- Relationship between age and maximum heart rate
- Feature relationships using visualisations

## 🤖 Machine Learning Models

Three classification models were trained and compared:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest

## 📈 Model Results

| Model | Test Accuracy |
|---|---:|
| Logistic Regression | 95.45% |
| KNN | 72.73% |
| Random Forest | 100% |

Random Forest scored highest on the test set in this experiment.

## ⚠️ Limitations

- The dataset is small (109 records), so the test set contains only about 22 patients. Scores such as 100% should be treated with caution, as they may not generalise to new data.
- Next steps: cross-validation, hyperparameter tuning, and testing on a larger dataset for more reliable results.

## 🚀 How to Run

```bash
git clone https://github.com/omkar2304-git/Heart-Disease-Classification.git
cd Heart-Disease-Classification
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Then open the notebook file in the repository and run the cells in order.

## 👤 Author

**Omkar Tasnuse**
B.Sc. Computer Science student | Aspiring AI/ML Intern
[LinkedIn](https://www.linkedin.com/in/omkar-m-tasnuse-a787b7395/) · [GitHub](https://github.com/omkar2304-git)
