# Sonar Rock vs Mine Prediction

A machine learning model that predicts whether an object is a rock or a mine based on sonar data. The model uses logistic regression to classify sonar readings with 85.7% accuracy on test data.

## Overview

This project uses sonar data to distinguish between rocks and mines underwater. The dataset contains 208 samples with 60 numerical features representing sonar frequencies, labeled as either 'R' (rock) or 'M' (mine).

##  Install Dependencies
`pip install -r requirements.txt`

## Dataset Details
- Total samples: 208
- Features: 60 (numerical sonar frequencies)
- Classes: 2 (Rock: 97 samples, Mine: 111 samples)
- Train/Test split: 80/20

## Model Performance
- Training accuracy: 83.7%
- Test accuracy: 85.7%


