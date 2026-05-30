🛡️ MalJPEG: Machine Learning-Based Detection of Malicious JPEG Images

📌 Project Overview

MalJPEG is a cybersecurity-focused machine learning project developed to identify malicious JPEG images by analyzing their internal file structure, metadata, and marker-based characteristics.

Cyber attackers increasingly use image files as carriers for hidden malicious payloads because they appear harmless to users and can bypass traditional security mechanisms. This project leverages machine learning techniques to analyze JPEG-specific features and accurately classify images as Benign or Malicious.

The project was further enhanced with advanced feature extraction, additional machine learning models, metadata analysis, and visual comparison capabilities to improve detection performance and interpretability.

🎯 Problem Statement

JPEG images are among the most commonly shared file formats on the internet. Attackers can exploit JPEG file structures to hide malicious payloads within image metadata, markers, or unused file segments.

Traditional antivirus systems primarily rely on signature-based detection and often fail to identify image-based threats.

The challenge is to develop an intelligent detection system capable of distinguishing malicious JPEG images from legitimate ones using machine learning and JPEG structural analysis.

🎯 Objectives
Detect malicious JPEG images using Machine Learning.
Analyze JPEG file structures and metadata.
Extract marker-based features from image files.
Compare benign and malicious JPEG characteristics.
Evaluate multiple machine learning algorithms.
Improve image-based malware detection techniques.
Visualize classification results using graphs and comparison tools.
🏗️ Existing Project

The existing implementation focuses on extracting fundamental JPEG marker-based features and classifying images using traditional machine learning models.

Features Used
DQT (Define Quantization Table)
DHT (Define Huffman Table)
APP1 Marker Count
COM Marker Count
Total JPEG Marker Count
Algorithms Used
Random Forest Classifier
LightGBM Classifier
Workflow
Dataset Collection
JPEG Feature Extraction
Feature Preprocessing
Model Training
Classification
Accuracy Evaluation
Result Visualization
🚀 Enhanced Project

The enhanced version extends the capabilities of the original system through advanced feature extraction, additional machine learning algorithms, payload simulation, and visualization techniques.

Additional Enhancements

✅ EXIF Metadata Analysis

✅ Entropy-Based Features

✅ JPEG Segment Size Analysis

✅ Payload Injection Simulation

✅ Benign vs Malicious Image Comparison

✅ Dynamic Image Selection

✅ Accuracy Graph Visualization

✅ Multi-Model Performance Comparison

Advanced Features Extracted
Feature	Description
DQT_num	Number of Quantization Tables
DHT_num	Number of Huffman Tables
APP1_num	APP1 Marker Frequency
COM_num	Comment Marker Frequency
Marker_total	Total JPEG Marker Count
EXIF Size	Metadata Size
EXIF Presence	Whether Metadata Exists
Entropy	Randomness Measure
Bytes After EOI	Hidden Data Detection
Segment Statistics	JPEG Structural Analysis
📂 Dataset
Benign Images
Oxford5K Dataset
Real-world JPEG images
Building and landscape photographs
Used as clean image samples
Malicious Images
Malware Benign Image Sample Dataset
Malware-related image samples
Used for malicious image analysis
Includes hidden payload characteristics
⚙️ Technologies Used
Python
Google Colab
NumPy
Pandas
OpenCV
Matplotlib
Pillow (PIL)
Scikit-Learn
LightGBM
XGBoost
🤖 Machine Learning Models
Existing Project
Random Forest
LightGBM
Enhanced Project
Random Forest
LightGBM
Logistic Regression
XGBoost
🔄 Project Workflow
Dataset Collection
        ↓
JPEG Feature Extraction
        ↓
Metadata Analysis
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Model Training
        ↓
Classification
        ↓
Performance Evaluation
        ↓
Visualization & Analysis
📊 Performance Metrics

The following evaluation metrics were used:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
📈 Visualizations

The project generates:

Accuracy Comparison Graphs
ROC Curves
Feature Importance Graphs
Benign vs Malicious Image Comparison
Existing vs Enhanced Model Comparison
🔐 Cybersecurity Significance

This project demonstrates how machine learning can be applied to identify malicious JPEG images that appear visually identical to legitimate images.

The proposed solution can be integrated into:

Email Security Systems
Malware Analysis Platforms
Digital Forensics Tools
Web Application Security
Secure File Upload Systems
🔮 Future Enhancements
Deep Learning-Based Detection (CNN)
Real-Time Image Scanner
Streamlit Web Application
Malware Family Classification
Hybrid Static and Dynamic Analysis
Cloud-Based Detection Service
API Integration for Security Platforms
📚 Research Contribution

This project contributes to the field of:

Cybersecurity
Malware Analysis
Digital Forensics
Machine Learning-Based Threat Detection
Image-Based Malware Research
👩‍💻 Author

Srija Bojja
B.Tech – Information Technology

Areas of Interest

Cybersecurity
Data Analytics
Machine Learning
Digital Forensics
Artificial Intelligence

⭐ MalJPEG demonstrates how machine learning can transform traditional image security by detecting hidden threats embedded within seemingly harmless JPEG files.
