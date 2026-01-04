# Customer Churn Prediction – Mini Machine Learning Project

## Project Overview
This project predicts whether a customer will leave a service (churn) using basic machine learning techniques.  
It is implemented as an end-to-end ML workflow and follows the instructions of the AI/ML Fresher Assignment.

---

## Objective
To build a simple and clean machine learning model that predicts customer churn using a public dataset and evaluates the model using standard classification metrics.

---

## Dataset
- **Dataset Name:** Telecom Customer Churn Dataset  
- **Source:** Public dataset (Kaggle / UCI Repository)  
- **Target Variable:** `Churn`  
  - 0 → No (Customer stays)
  - 1 → Yes (Customer leaves)

The dataset includes customer demographics, service usage, and billing information.

---

## Project Structure
├── Telco Customer Churn.ipynb
├── README.md

---

## How to Run the Project

1. Clone the GitHub repository:
   ```bash
   git clone <your-github-repository-link>

2. Open the Jupyter Notebook:
   jupyter notebook "Telco Customer Churn.ipynb"

3. Run the notebook cells step by step to:

    - Load and explore the dataset
   
    - Handle missing values

    - Encode categorical variables

    - Split the dataset into training and test sets

    - Train machine learning models

    - Evaluate model performance

## Data Preparation

  - Loaded the dataset using Pandas

  - Checked and handled missing values

  - Converted categorical features into numerical format

  - Split the data into training and testing sets

## Models Used

The following machine learning models were implemented:

 - Logistic Regression

 - Decision Tree Classifier

Although only one model was required, both models were trained to compare performance.

## Model Evaluation

Models were evaluated using:

 - Accuracy

 - Confusion Matrix

 - Precision, Recall, and F1-score

## Results
## Decision Tree Classifier

 - Accuracy: 78%

 - Churn Precision: 63%

 - Churn Recall: 35%

 - Churn F1-score: 0.45

The Decision Tree performs well for non-churn customers but misses many actual churn customers.

## Logistic Regression

 - Accuracy: 80%

 - Churn Precision: 65%

 - Churn Recall: 52%

 - Churn F1-score: 0.57

Logistic Regression detects more churn customers and provides a better balance between precision and recall.

## Final Conclusion

Logistic Regression is the preferred model for this churn prediction problem.
Even though both models show similar accuracy, Logistic Regression performs significantly better in identifying churn customers, which is more important for real-world business decisions.

