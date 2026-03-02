# Anomaly-detection
Anomaly detection
# 🔍 Credit Card Fraud Detection using Anomaly Detection

A comprehensive machine learning project for detecting fraudulent credit card transactions using multiple anomaly detection algorithms. This project demonstrates practical implementation of unsupervised learning techniques for fraud detection on highly imbalanced datasets.

## 📊 Project Overview

This notebook implements and compares four different anomaly detection algorithms to identify fraudulent credit card transactions:

- **Isolation Forest** - Tree-based anomaly detection for high-dimensional data
- **Local Outlier Factor (LOF)** - Density-based local anomaly detection
- **K-Nearest Neighbors (KNN)** - Distance-based anomaly detection
- **Z-Score Statistical Method** - Statistical threshold-based detection

## 🎯 Key Features

- ✅ Complete end-to-end anomaly detection pipeline
- 📈 Comprehensive Exploratory Data Analysis (EDA)
- 🤖 Multiple ML algorithms with side-by-side comparison
- 📊 Rich visualizations (confusion matrices, ROC curves, PCA plots)
- 🎨 Interactive Jupyter notebook with detailed explanations
- 🔄 Automatic fallback to synthetic data if dataset unavailable
- 📉 Handling of highly imbalanced datasets (0.17% fraud rate)

## 📁 Dataset

Uses the **Credit Card Fraud Detection Dataset** containing:
- 284,807 transactions over 2 days
- 492 fraudulent transactions (0.17%)
- 28 anonymized PCA-transformed features (V1-V28)
- Time and Amount features
- Highly imbalanced classification problem
