# Online Payment Fraud Detection

This project focuses on detecting fraudulent online payment transactions using machine learning.
It includes a real-world transaction dataset, a notebook for analysis/modeling, and supporting documentation.

## Project Objective

Build a fraud detection workflow that can classify transactions as:
- Fraudulent (`isFraud = 1`)
- Legitimate (`isFraud = 0`)

## Dataset

Source: Kaggle (historical online payment transactions)

Key columns used in analysis:
- `step`: Time step (1 step = 1 hour)
- `type`: Transaction type
- `amount`: Transaction amount
- `nameOrig`, `nameDest`: Sender and receiver identifiers
- `oldbalanceOrg`, `newbalanceOrig`: Sender balance before/after transaction
- `oldbalanceDest`, `newbalanceDest`: Receiver balance before/after transaction
- `isFraud`: Fraud label

## Project Structure

- `online_fraud_detection.ipynb`: Main notebook for EDA, preprocessing, and model work
- `onlinefraud.csv`: Transaction dataset
- `data-description.txt`: Dataset and column descriptions
- `README.md`: Project overview

## How to Run

1. Open `online_fraud_detection.ipynb` in Jupyter or VS Code.
2. Ensure common Python libraries are installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Run notebook cells in order.

## Outcome

This project provides a practical base for building and evaluating fraud detection models for online payments.