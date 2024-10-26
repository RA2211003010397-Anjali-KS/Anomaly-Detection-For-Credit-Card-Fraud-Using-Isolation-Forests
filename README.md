# Anomaly-Detection-For-Credit-Card-Fraud-Using-Isolation-Forests


---

# Credit Card Fraud Detection Project

## Overview

This project implements various anomaly detection algorithms to identify potential credit card fraud in transaction data. Using a dataset of credit card transactions, the goal is to develop models that can effectively differentiate between legitimate transactions and fraudulent ones.

## Algorithms Implemented

This repository contains implementations of the following algorithms:

- **Isolation Forest**: An ensemble method that isolates anomalies by randomly selecting a feature and splitting the data.
- **Support Vector Machine (SVM)**: A supervised learning model that classifies transactions based on support vectors, particularly effective for high-dimensional data.
- **Local Outlier Factor (LOF)**: A density-based anomaly detection method that identifies anomalies based on their local density compared to their neighbors.
- **k-Nearest Neighbors (k-NN)**: A simple, intuitive method that classifies points based on the majority label of their nearest neighbors.

## Dataset

The project utilizes the publicly available credit card transactions dataset, which includes features such as transaction amounts and time, alongside a label indicating whether a transaction is fraudulent.

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   ```

2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```

3. Open the Jupyter Notebook or Google Colab files to run the algorithms and visualize the results.

## Results

The effectiveness of each algorithm is compared based on metrics like accuracy, precision, recall, and F1 score. A bar graph visualizes the performance of the different algorithms, making it easy to identify the best-performing model for credit card fraud detection.

