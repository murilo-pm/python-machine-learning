# Credit Score Prediction with Python and Machine Learning

## Overview

This project demonstrates how Machine Learning can be used to predict a customer's credit score based on historical financial and behavioral data.

Using Python and Scikit-learn, the project builds, trains, and evaluates classification models capable of automatically categorizing customers into different credit score levels.

The solution follows a complete Machine Learning workflow, including data preparation, feature encoding, model training, evaluation, comparison, and prediction on new customer data.

---

## Business Case

Financial institutions rely on credit scores to estimate the level of risk associated with lending money or offering financial products.

In this case study, a bank needs to automate the credit scoring process by analyzing customer information and predicting whether a customer's credit profile should be classified as:

* Good
* Standard
* Poor

The objective is to support faster, more consistent, and data-driven credit decisions.

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Import

The customer dataset is loaded into a Pandas DataFrame for analysis and preprocessing.

### 2. Data Exploration

The dataset structure is inspected to identify data types, categorical variables, and potential preprocessing requirements.

### 3. Data Preprocessing

Since Machine Learning algorithms require numerical input, categorical variables are converted into numeric representations using the **LabelEncoder** class.

The preprocessing stage includes:

* Feature encoding
* Dataset validation
* Data preparation for model training

---

### 4. Feature Selection

The dataset is divided into:

* **Features (X):** customer information used as input.
* **Target (y):** the credit score to be predicted.

Columns that should not influence the prediction, such as customer identifiers, are excluded from the training dataset.

---

### 5. Train-Test Split

The dataset is divided into two subsets:

* **70% Training Data**
* **30% Testing Data**

The training set teaches the model to recognize patterns, while the testing set evaluates its ability to make predictions on unseen data.

This process helps measure how well the model generalizes to real-world scenarios.

---

### 6. Model Training

Two supervised Machine Learning classification algorithms are trained and compared.

#### Random Forest Classifier

Random Forest combines multiple decision trees to produce more accurate and stable predictions.

Advantages:

* High predictive performance
* Handles complex relationships
* Less sensitive to noisy data
* Excellent for structured datasets

---

#### K-Nearest Neighbors (KNN)

KNN classifies new observations by comparing them with the most similar samples in the dataset.

Advantages:

* Simple to understand
* Easy to implement
* Effective on smaller datasets

Limitations:

* Slower during prediction
* Sensitive to feature scaling
* Performance decreases with very large datasets

---

### 7. Model Evaluation

Both models are evaluated using **Accuracy Score**, which measures the percentage of correct predictions.

The model with the highest accuracy is selected for production.

---

### 8. Prediction

After selecting the best-performing model, new customer records are preprocessed using the same encoding strategy and submitted to the trained model for automatic credit score prediction.

---

## Skills Demonstrated

* Python Programming
* Machine Learning Fundamentals
* Supervised Learning
* Classification Models
* Data Preprocessing
* Feature Encoding
* Dataset Preparation
* Model Training
* Model Evaluation
* Model Comparison
* Predictive Analytics
* Credit Risk Analysis
* Scikit-learn
* Pandas Data Manipulation

---

## Applications in Information Technology

Although this project focuses on credit score prediction, the same workflow is widely applicable across different IT domains.

### FinTech

* Credit scoring
* Loan approval systems
* Fraud detection
* Customer risk assessment
* Banking automation
* Financial decision support
* Customer segmentation
* Regulatory compliance support

### Application Support

* Ticket classification
* Incident prioritization
* Predictive issue categorization
* Operational analytics
* Customer behavior analysis
* SLA monitoring

### Infrastructure & Cloud

* Failure prediction
* Capacity planning
* Resource utilization analysis
* Infrastructure monitoring
* Predictive maintenance
* Performance optimization

### Engineering & IT Operations

* Log analysis
* Event classification
* Root cause analysis
* Operational dashboards
* Intelligent automation
* Decision support systems

---

## Learning Outcomes

This project demonstrates practical experience with:

* Preparing real-world datasets for Machine Learning
* Converting categorical variables into numerical features
* Training multiple classification algorithms
* Comparing predictive models
* Evaluating model performance
* Building an end-to-end Machine Learning pipeline
* Applying predictive analytics to business problems

---

## Future Improvements

Possible enhancements include:

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Feature importance analysis
* Confusion matrix visualization
* Precision, Recall and F1-Score evaluation
* ROC Curve analysis
* Pipeline automation
* Model persistence using Joblib or Pickle
* Deployment as a REST API
* Interactive dashboard with Streamlit
* Integration with SQL databases
* Integration with cloud platforms such as Microsoft Azure or AWS

---

## Author

**Murilo M.**

IT Support Engineer | Python | Machine Learning | Data Analytics | Automation | Microsoft Technologies
