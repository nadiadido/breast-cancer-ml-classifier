# Breast Cancer Malignancy Classifier

A machine learning project that predicts whether a breast tumor is malignant or benign using clinical biopsy measurements.

## Results
- **96.49% accuracy** on unseen patient data
- Correctly classified 110 out of 114 patients
- Only 4 misclassifications (3 false negatives, 1 false positive)

## Motivation
This project was inspired by my work as an Imaging Physics Research Intern at MD Anderson Cancer Center, where I work on ML-based image segmentation and cancer diagnostics. I built this to deepen my understanding of how machine learning can be applied to clinical cancer data.

## What it does
- Loads and explores the Wisconsin Breast Cancer Dataset (569 patients, 30 features)
- Visualizes malignant vs benign diagnosis distribution
- Trains a Random Forest Classifier on 80% of the data
- Evaluates performance on the remaining 20%
- Visualizes a confusion matrix and top 10 most important diagnostic features

## Tools Used
- Python, Pandas, NumPy
- Scikit-learn (Random Forest Classifier)
- Matplotlib, Seaborn

## Key Finding
The model identified **worst area**, **worst concave points**, and **worst radius** as the strongest predictors of malignancy — consistent with clinical research on tumor morphology.

## Author
Nadia — Honors Biology, University of Houston | MD Anderson Cancer Center Research Intern
