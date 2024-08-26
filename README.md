# Network Intrusion Detection System Using KDD Dataset

This repository contains a comprehensive implementation of a Network Intrusion Detection System (NIDS) using the KDD dataset. The project focuses on detecting malicious activities in a network by applying various machine learning algorithms on the KDD dataset, a widely-used benchmark for evaluating intrusion detection systems.

# Malicious activities in a network like:
- DOS attack
- Normal attack
- Probe
- R2L
- U2R

## Features

- **Data Preprocessing**: 
  - Cleaning and transforming the raw KDD dataset.
  - Feature selection and extraction to optimize the dataset for training.
  - Data normalization and splitting into training and testing sets.

- **Machine Learning Models**: 
  - **Support Vector Machine (SVM)**: A robust classifier used to identify different types of intrusions.
  - **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm applied to classify network activities.
  - **Decision Tree**: A tree-structured model for making sequential decisions based on the features of the dataset.
  - **Random Forest**: An ensemble learning method that combines multiple decision trees to improve classification accuracy.

- **Model Training and Evaluation**: 
  - Training the models on the processed KDD dataset.
  - Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
  - Comparing the effectiveness of different algorithms in detecting network intrusions.

- **Visualization and Analysis**: 
  - Visual representation of data distribution and model performance.
  - Analysis of the strengths and weaknesses of each model.

## Usage

- Clone the repository.
- Install required dependencies listed in `requirements.txt`.
- Follow the instructions in the Jupyter notebooks to preprocess the data, train models, and evaluate their performance.

## Applications

This project is ideal for anyone interested in network security, machine learning, and data science. It provides a solid foundation for understanding how to apply machine learning techniques to real-world cybersecurity problems. The methods and models developed here can be extended or modified to work with other datasets or specific network environments.

---

This repository is a valuable resource for researchers, students, and professionals looking to explore and implement network intrusion detection systems using machine learning.
