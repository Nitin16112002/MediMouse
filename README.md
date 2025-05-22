# MediMouse 
**Predicting Infection Outcomes Based on Medicine Dosage Using Machine Learning**

## Overview

MediMouse is a machine learning project that simulates a medical study on mice infected with a virus. Each mouse was administered varying doses of two different medicines. After two weeks, the infection status of each mouse was recorded. The goal of this project is to build a classification model that can predict whether a mouse remains infected based on the two dosage values.

This project demonstrates how data-driven approaches can support treatment strategy development in biomedical research.

## Project Highlights

- **Classification Model**: Linear Support Vector Machine (SVM)
- **Feature Inputs**: Dosage levels of Medicine 1 and Medicine 2
- **Target Output**: Infection status (`0` = Not Infected, `1` = Still Infected)
- **Model Performance**:
  - Training Accuracy: **100%**
  - Test Accuracy: **100%**
  - Cross-Validation Score: **100%**

## Dataset

The dataset simulates:
- 2 continuous features: `Medicine 1` and `Medicine 2` dosages.
- 1 binary target: `Infection Status` (0 or 1).

The data is linearly separable, which makes it suitable for a linear SVM classifier.

## Model Configuration

The model was built using:
- **Algorithm**: Support Vector Machine (SVM)
- **Kernel**: Linear
- **Regularization Parameter (C)**: 0.01

```python
{'C': 0.01, 'kernel': 'linear'}
