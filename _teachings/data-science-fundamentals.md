---
layout: course
title: "Machine Learning Workshop: End-to-End Pipeline & Medical Classification"
description: "A hands-on engineering workshop focused on building, evaluating, and optimizing a supervised machine learning pipeline for tumor diagnosis using the Breast Cancer Wisconsin dataset."
instructor: Ghassen Marrakchi
year: 2026
location: University of Tirana
time: Tuesday, 26 May 2026
course_id: ml-workshop-medical-classification
schedule:
  - Part: 1
    date: May 26
    topic: Data Loading & Exploratory Data Analysis (EDA)
    description: Automated and manual data ingestion using pandas and numpy. Auditing dimensions, mapping class distributions, and visualizing feature variances using seaborn and matplotlib.
    materials:
      - name: Workshop Repository & Notebook
        url: https://github.com/MARRAKCHIGhassen/Workshops/tree/main/Machine%20Learning%20Workshop%3A%20End-to-End%20Pipeline%20%26%20Medical%20Classification

  - Part: 2
    date: May 26
    topic: Preprocessing & Baseline Metrics
    description: Implementing a stratified 80/20 train/test split and normalizing features with StandardScaler. Constructing a baseline Decision Tree and decoding evaluation metrics (Accuracy, Precision, Recall, Confusion Matrices, ROC).
    materials:
      - name: Workshop Repository & Notebook
        url: https://github.com/MARRAKCHIGhassen/Workshops/tree/main/Machine%20Learning%20Workshop%3A%20End-to-End%20Pipeline%20%26%20Medical%20Classification

  - Part: 3
    date: May 26
    topic: The Scaling Experiment
    description: A controlled visual and empirical experiment using KNeighborsClassifier trained on both unscaled and scaled data to prove the critical impact of normalization on distance-based models.
    materials:
      - name: Workshop Repository & Notebook
        url: https://github.com/MARRAKCHIGhassen/Workshops/tree/main/Machine%20Learning%20Workshop%3A%20End-to-End%20Pipeline%20%26%20Medical%20Classification

  - Part: 4
    date: May 26
    topic: Pipeline Optimization & Production Inference
    description: Building modular Pipeline structures and running automated GridSearchCV across Decision Trees, KNN, Random Forests, and Logistic Regression. Concluding with simulated real-time inference on a raw patient record.
    materials:
      - name: Workshop Repository & Notebook
        url: https://github.com/MARRAKCHIGhassen/Workshops/tree/main/Machine%20Learning%20Workshop%3A%20End-to-End%20Pipeline%20%26%20Medical%20Classification
---

## Workshop Overview

This workshop is dedicated to model engineering and supervised learning. We are adopting a strict engineering mindset: no magic, just applied mathematics and industry standards. In this session, participants build, evaluate, and optimize a complete Machine Learning system, from raw data ingestion to final predictive inference.

## The Use Case: Automated Tumor Diagnosis

We work with real-world medical data utilizing the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

* **The Mission:** Engineer a robust binary classification algorithm capable of accurately diagnosing a tumor as **Benign** or **Malignant** by analyzing 30 distinct digitized cellular features.
* **The Business & Ethical Challenge:** In healthcare, diagnostic errors carry life-or-death consequences. We explore why standard "Accuracy" is a dangerous metric in medicine, and learn how to force our algorithm to prioritize the minimization of false negatives (missed diagnoses) using custom Recall scorers.

## Technical Stack

This workshop relies exclusively on the industry-standard Python data stack:
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (Pipelines, Model Selection, Metrics, Classifiers)
* **Visualization:** `matplotlib`, `seaborn`

## Core Concept: Mastering Scikit-Learn

While Deep Learning (TensorFlow/PyTorch) often gets the spotlight, **Scikit-Learn** is the absolute industry standard for classical Machine Learning. Mastering its unified catalog of algorithms and robust tools for data preprocessing and pipeline creation is the mandatory first step for any Data Scientist or Machine Learning Engineer.

## Setup and Execution

All workshop materials are freely available. To participate:
1.  Access the [Workshop Repository on GitHub](https://github.com/MARRAKCHIGhassen/Workshops/tree/main/Machine%20Learning%20Workshop%3A%20End-to-End%20Pipeline%20%26%20Medical%20Classification).
2.  Open the Jupyter Notebook locally or directly in Google Colab.
3.  Ensure your Python environment has the required dependencies (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
