# loan-approval-predictor

A Machine Learning project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant information. This project demonstrates a complete machine learning workflow, from data preprocessing to model evaluation and comparison.

---

## Project Overview

The objective of this project is to build classification models capable of predicting loan approval decisions using applicant financial and personal information.

The notebook includes:

- Data loading
- Data exploration
- Data preprocessing
- Feature engineering
- Model training
- Model comparison
- Performance evaluation

---

## Dataset

The project uses the **Loan Approval Dataset** (`loan_approval_dataset.csv`).

The dataset contains applicant information such as:

- Income
- Loan amount
- Credit score
- Asset values
- Education
- Employment status
- Other financial features

Target variable:

- **loan_status**
  - Approved
  - Rejected

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Pipeline

### 1. Data Preprocessing

The preprocessing pipeline includes:

- Removing unnecessary spaces from categorical values
- Handling missing numerical values using the **median**
- Handling missing categorical values using the **most frequent value**
- One-Hot Encoding categorical features
- Standardizing numerical features using **StandardScaler**

---

### 2. Data Split

The dataset is divided into:

- 80% Training set
- 20% Test set

using `train_test_split()`.

---

### 3. Models Trained

Three classification algorithms were evaluated:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

### 4. Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Cross-validation score

---

## Project Structure

```
Loan-Approval-Predictor/
│
├── loan approval predictor.ipynb
├── loan_approval_dataset.csv
├── README.md
```

---

## Results

The models were compared based on their predictive performance on the test set.

The notebook provides:

- Classification reports
- Confusion matrices
- Cross-validation scores
- Accuracy comparison between models

The best-performing model can be selected according to the evaluation metrics.

---


## Example Workflow

1. Load the dataset.
2. Explore the data.
3. Handle missing values.
4. Encode categorical features.
5. Scale numerical features.
6. Train multiple machine learning models.
7. Compare model performance.
8. Predict loan approval.

---


