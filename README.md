Custom Bagging Classifier & Regressor
📌 Overview

This repository implements Bagging (Bootstrap Aggregating) from scratch for both classification and regression tasks in Machine Learning.
Bagging is an ensemble method that combines predictions from multiple base learners trained on bootstrapped subsets of the dataset, reducing variance and improving stability.

⚡ Features

Custom implementation of BaggingClassifier and BaggingRegressor

Works with any base learner (e.g., Decision Trees, SVM, KNN, etc.)

Supports parallel base estimators

Handles both classification (majority vote) and regression (average prediction)

Lightweight and easy to integrate

🛠 How It Works

Draw multiple bootstrap samples from the training set.

Train a chosen base learner on each sample.

Combine predictions:

Classification → Majority voting

Regression → Averaging

Output the aggregated result.

📊 Advantages

Reduces overfitting of high-variance models

Improves accuracy & stability

Easy to extend with any ML algorithm

📂 Project Structure
├── custom_bagging.py   # Implementation of BaggingClassifier & BaggingRegressor
├── examples.ipynb      # Example usage with datasets
├── README.md           # Project documentation
