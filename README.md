# MalJPEG: Machine Learning Based Solution for Detection of Malicious JPEG Images

## Overview

MalJPEG is a cybersecurity and machine learning project designed to detect malicious JPEG images by analyzing JPEG file structures, metadata, and marker-based characteristics. Attackers often embed malicious payloads within JPEG files to bypass traditional security mechanisms. This project uses machine learning techniques to distinguish between benign and malicious JPEG images.

## Problem Statement

JPEG images are widely used across websites, social media platforms, and communication applications. Cyber attackers can exploit JPEG file structures to conceal malware and malicious code. Traditional antivirus solutions may fail to identify these threats, making automated machine learning-based detection essential.

## Objectives

* Detect malicious JPEG images using machine learning.
* Extract JPEG marker-based features.
* Compare benign and malicious image characteristics.
* Improve cybersecurity defenses against image-based attacks.

## Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* OpenCV
* Scikit-Learn
* XGBoost
* LightGBM
* Matplotlib

## Dataset

The project utilizes:

1. Oxford5k Dataset (Benign Images)
2. Malware Benign Image Sample Dataset

These datasets provide a balanced collection of benign and malicious JPEG images for training and evaluation.

## Feature Extraction

Features extracted from JPEG files include:

* DQT Marker Count
* DHT Marker Count
* APP Marker Analysis
* COM Marker Analysis
* JPEG Segment Sizes
* Metadata Characteristics
* Entropy-Based Features
* Marker Frequency Analysis

## Machine Learning Models

The following models were evaluated:

* Random Forest Classifier
* Logistic Regression
* XGBoost Classifier
* LightGBM Classifier

## Results

The trained models successfully distinguished malicious JPEG images from benign images using extracted JPEG structural features.

Performance metrics evaluated:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

## Project Workflow

1. Dataset Collection
2. JPEG Feature Extraction
3. Data Preprocessing
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Visualization and Analysis

## Future Enhancements

* Deep Learning-Based Detection
* Real-Time Image Scanning
* Streamlit Web Application
* Malware Family Classification
* Hybrid Static and Dynamic Analysis

## Author

Srija Bojja

B.Tech Information Technology

Cybersecurity & Data Analytics Enthusiast
