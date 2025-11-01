# loan-status-prediction-system

A Machine Learning project that predicts loan approval status based on applicant data using classification algorithms. The notebook includes complete steps — from data preprocessing and feature encoding to model training, evaluation, and accuracy comparison. Built using Python, pandas, NumPy, seaborn, and scikit-learn.

## 🚀 Project Overview

The aim of this project is to automate the **loan approval process** by leveraging machine learning algorithms.  
Financial institutions can use this model to reduce manual work and make faster, data-driven decisions.

---

## 📂 Dataset Details

The dataset contains applicant information such as:

| Feature | Description |
|----------|--------------|
| `Gender`, `Married`, `Dependents` | Demographic information |
| `ApplicantIncome`, `CoapplicantIncome` | Financial details |
| `LoanAmount`, `Loan_Amount_Term` | Loan details |
| `Credit_History` | Applicant credit record |
| `Property_Area` | Urban/Semiurban/Rural |
| `Loan_Status` | Target variable (Y/N) |

## 🧠 Features and Steps

1. **Data Loading and Exploration**
   - Load dataset using pandas.
   - Inspect data types, missing values, and overall structure.

2. **Data Cleaning and Preprocessing**
   - Handle missing values.
   - Encode categorical variables using LabelEncoder or one-hot encoding.
   - Normalize or scale numeric data if necessary.

3. **Exploratory Data Analysis (EDA)**
   - Visualize data distributions using seaborn and matplotlib.
   - Explore relationships between applicant income, loan amount, credit history, and loan status.

4. **Model Building**
   - Train different classification models (e.g., Logistic Regression, Decision Tree, Random Forest, or KNN).
   - Split data into **training** and **testing** sets using `train_test_split`.

5. **Model Evaluation**
   - Evaluate models using metrics like **accuracy score**, **confusion matrix**, and **classification report**.
   - Compare performance of different models.

6. **Final Prediction**
   - Select the best-performing model.
   - Predict loan status for unseen test data.

---

## 🧩 Technologies Used

| Tool / Library | Purpose |
|-----------------|----------|
| **Python** | Programming language |
| **pandas, numpy** | Data handling and analysis |
| **matplotlib, seaborn** | Data visualization |
| **scikit-learn** | Machine learning algorithms and evaluation metrics |
| **Jupyter Notebook** | Interactive code environment |

---

## 📊 Example Output

```python
Accuracy Score: 0.85

