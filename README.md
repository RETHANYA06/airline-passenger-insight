# ✈️ Airline Passenger Insight

A data science project that explores airline passenger satisfaction and predicts whether a passenger is likely to be satisfied using machine learning.

## 📌 Project Overview

This project analyzes passenger travel details, service ratings, and flight delays to identify patterns associated with passenger satisfaction. It includes data preprocessing, exploratory data analysis (EDA), machine learning model evaluation, and an interactive prediction prototype.

> **Dataset note:** This project uses synthetic data for educational and demonstration purposes. Findings do not represent actual airline operations.

## 🎯 Objectives

- Analyze passenger satisfaction patterns.
- Explore the relationship between flight delays and satisfaction.
- Examine passenger service ratings.
- Compare classification models.
- Build a prototype that predicts passenger satisfaction from travel and service details.

## 🛠️ Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook
- IPyWidgets

## 🔄 Project Workflow

1. Load and merge the passenger, flight, delay, service-rating, and feedback datasets.
2. Check data quality, handle missing values, remove duplicates, and prepare features.
3. Perform exploratory data analysis and visualize satisfaction patterns.
4. Train and compare classification models.
5. Evaluate the selected Logistic Regression model using a held-out test set.
6. Create an interactive prototype for passenger satisfaction prediction.

## 📊 Key Findings

- Dissatisfied passengers had higher average delays than satisfied passengers in the synthetic dataset.
- Average departure delay was approximately 25 minutes for dissatisfied passengers and 18.8 minutes for satisfied passengers.
- Average arrival delay was approximately 32.6 minutes for dissatisfied passengers and 26.1 minutes for satisfied passengers.

These are exploratory observations from synthetic data, not real-world airline findings.

## 🤖 Model Evaluation

The selected Logistic Regression model achieved **65% test accuracy** on a held-out test set of 100 records.

| Metric | Dissatisfied | Satisfied |
|---|---:|---:|
| Precision | 0.72 | 0.58 |
| Recall | 0.61 | 0.70 |
| F1-score | 0.66 | 0.64 |

The model demonstrates a working classification pipeline, but its performance is limited and should be improved and validated on real-world data before practical use.

## 🧪 Interactive Prototype

The notebook includes an interactive form where users can enter passenger and flight details to receive a predicted satisfaction class and model-estimated probabilities.

## ⚠️ Limitations

- The dataset is synthetic and may not capture real passenger behavior.
- The test accuracy is 65%, so predictions can be incorrect.
- Model-estimated probabilities are not guarantees of actual passenger satisfaction.
- Real-world deployment would require representative data, further validation, and monitoring.

## 🚀 Future Improvements

- Evaluate the model using genuine, appropriately licensed airline passenger data.
- Improve feature engineering and model performance.
- Add explainability to identify influential prediction features.
- Build a web-based interface for easier access.
- Validate probability calibration and performance across passenger groups.

## 👩‍💻 Author

**Rethanya V**

GitHub: [RETHANYA06](https://github.com/RETHANYA06)

---

*Created for educational and data science portfolio purposes.*
