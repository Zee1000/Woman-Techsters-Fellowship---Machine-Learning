# Hiring Salary Prediction – Machine Learning Project

## Project Overview
This project applies **Multivariate Linear Regression** to predict employee salary based on multiple input features.

The model estimates salary using:
- Years of Experience
- Test Score (out of 10)
- Interview Score (out of 10)

The objective is to demonstrate data preprocessing, model training, and prediction using Scikit-learn in Google Colab.

---

## Dataset
The dataset (`hiring.csv`) contains hiring statistics including:
- `experience`
- `test_score`
- `interview_score`
- `salary`

Some preprocessing was required:
- Handling missing values
- Converting text-based numerical values (e.g., "five", "seven") into numeric format
- Cleaning the dataset before model training

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

## Model
A **LinearRegression** model from Scikit-learn was trained on the dataset.

The model learns coefficients for:
- Experience
- Test Score
- Interview Score

The trained model is then used to predict salaries for new candidates.

---

## Example Predictions
The model was used to predict salaries for:
- 2 years experience, 9 test score, 6 interview score
- 12 years experience, 10 test score, 10 interview score

---

## How to Run
Click the badge below to open in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1P15maGobOYRdEbz3zwDevzjx0DYAPA1g?usp=sharing)]


---

## Author
Zintle Thandile Mgwelo
Woman Techsters Fellowship – Machine Learning Track

