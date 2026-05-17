# part-1-neural-network-analysis
# README.md

# Neural Network Fundamentals and Training Behavior Analysis

## Project Overview

This project demonstrates the implementation and analysis of a feed-forward neural network for a supervised learning problem using a customer churn dataset.

The project covers:

* Dataset understanding
* Data preprocessing
* Neural network model building
* Model training and evaluation
* Hyperparameter experimentation
* Final reflection on neural network concepts

---

# Dataset Information

Dataset Name: customer_churn_nn.csv

Target Variable:

* churn

Input Features:

* region
* plan_type
* contract_type
* payment_method
* tenure_months
* monthly_charges_inr
* avg_login_days_per_month
* support_tickets_last_90_days
* payment_delay_days
* data_usage_gb
* satisfaction_score
* last_complaint_days_ago
* discount_percent
* autopay_enabled
* referral_count

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

---

# Steps Performed

## Task 1: Dataset Understanding

* Loaded dataset
* Checked shape and column types
* Checked missing values
* Generated statistical summary
* Visualized target variable distribution

## Task 2: Data Preprocessing

* Encoded categorical variables
* Applied feature scaling
* Split dataset into training and testing sets

## Task 3: Neural Network Model Building

* Built a feed-forward neural network
* Used ReLU activation function
* Used Sigmoid output activation
* Used Binary Crossentropy loss function
* Used Adam optimizer

## Task 4: Training and Evaluation

* Trained the model
* Evaluated test accuracy
* Generated confusion matrix
* Generated classification report

## Task 5: Hyperparameter Experimentation

Three experiments were performed by changing:

* Number of neurons
* Activation function
* Batch size
* Number of epochs

## Task 6: Final Reflection

Discussed:

* Role of weights and biases
* Importance of activation functions
* Learning rate effects
* Underfitting and overfitting

---

# Repository Structure

part-1-neural-network-analysis/

├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
├── model_comparison_table.csv
└── evaluation_outputs.png

---

# Conclusion

The neural network successfully learned customer churn patterns and achieved good prediction accuracy. Hyperparameter tuning improved model performance and demonstrated how neural network behavior changes with different configurations.
