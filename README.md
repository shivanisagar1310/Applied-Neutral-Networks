# Neural Network Fundamentals and Training Behavior Analysis

## Objective
The objective of this project is to build and analyze a feed-forward neural network model for predicting customer churn.

Target Variable:
- churn = 1 → Customer churned
- churn = 0 → Customer retained


## Dataset Information

Dataset: Customer Churn Dataset

Features include:

Categorical:
- region
- plan_type
- contract_type
- payment_method

Numerical:
- tenure
- monthly charges
- usage metrics
- satisfaction score
- complaint history
- referrals

Removed column:
- customer_id (identifier only)


## Task 1: Dataset Understanding

Performed:

✓ Shape of dataset  
✓ Missing value analysis  
✓ Statistical summary  
✓ Target distribution analysis


## Task 2: Data Preprocessing

Performed:

✓ Removed customer_id  
✓ One-hot encoding  
✓ Standard scaling  
✓ Train-test split


## Task 3: Neural Network Model

Architecture:
Input Layer
Dense Layer (32 neurons, ReLU)
Dense Layer (16 neurons, ReLU)
Output Layer (1 neuron, Sigmoid)

Loss Function:
Binary Crossentropy

Optimizer:
Adam


## Task 4: Model Evaluation

Metrics used:
- Accuracy
- Loss
- Confusion Matrix
- Classification Report


## Task 5: Hyperparameter Experiments

Compared:
- Neurons
- Learning rate
- Epochs
- Batch size


## Task 6: Reflection

Weights:
Determine importance of features.

Bias:
Shifts activation threshold.

Activation Function:
Introduces nonlinearity.

Learning Rate:
Too high → unstable
Too low → slow learning

Underfitting:
Poor train/test performance

Overfitting:
High train accuracy but low test accuracy

## Libraries Used
TensorFlow
Pandas
NumPy
Matplotlib
Scikit-learn
Seaborn
