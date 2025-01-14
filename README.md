# SMS-Spam-Filtering
### README for SMS Spam Filtering Project  

# SMS Spam Filtering  

This project focuses on building a machine learning-based SMS Spam Filtering system capable of classifying messages as either **Spam** or **Ham** (legitimate). It utilizes advanced text preprocessing, feature extraction techniques, and a range of machine learning models to achieve high accuracy and low error rates.  

---

## Table of Contents  
- [Introduction](#introduction)  
- [Features](#features)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [Future Scope](#future-scope)  

---

## Introduction  

Short Message Service (SMS) is a widely used communication medium, but it is frequently misused to send spam messages, leading to security risks, wasted time, and poor user experience. This project addresses the problem by implementing an efficient machine learning pipeline to classify SMS messages, ensuring accurate spam detection and user safety.  

---

## Features  
- Preprocessing of text data (noise removal, tokenization, etc.).  
- Feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency).  
- Evaluation of multiple classifiers:
  - Logistic Regression  
  - Support Vector Machines  
  - Naïve Bayes  
  - Decision Trees  
  - Random Forests  
  - AdaBoost  
  - Neural Networks  
- Implementation of grid search and cross-validation for model optimization.  
- Online learning approach for dynamic dataset handling.  
- Visualization of performance metrics.  

---

## Dataset  

The SMS Spam Collection Dataset was used, containing:  
  - 5572 messages:  
  - 4825 Ham (legitimate)  
  - 747 Spam  

The dataset is available in the `datasets` directory in `.csv` format.  

---

## Technologies Used  

- Python: Core programming language  
- Libraries:  
  - Scikit-learn: Model training, testing, and evaluation  
  - Pandas & NumPy: Data preprocessing and numerical computations  
  - Matplotlib: Visualization of metrics  
  - Pickle: Model persistence  

---

## Usage  

1. Prepare the dataset:  
   Place the dataset (`spam.csv`) in the `datasets` folder.  

2. Run the script for training and evaluation.  

3. For online learning visualization, execute. 

4. Results, including trained models and plots, will be saved in the `results` folder.  

---

## Results  

- Achieved a misclassification error rate of less than 5% using advanced classifiers.  
- Models evaluated using precision, recall, F1-score, and accuracy metrics.  

---

## Future Scope  

- Enhance handling of imbalanced datasets through scaling techniques.  
- Integrate the system with real-time SMS applications or messaging platforms.  
- Experiment with deep learning models for further improvements.  

---

## Acknowledgments  

- Dataset: SMS Spam Collection Dataset  
- Tools and Libraries: Scikit-learn, Pandas, NumPy 

---  
