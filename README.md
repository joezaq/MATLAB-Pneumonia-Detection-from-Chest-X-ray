# MATLAB-Pneumonia-Detection-from-Chest-X-ray
This project develops a machine learning system for automated pneumonia detection from chest X-ray images. The aim is to improve diagnostic accuracy, support medical professionals, and enable faster clinical decision-making through intelligent image classification.

## Overview
The system applies image preprocessing, feature extraction, and machine learning techniques to classify chest X-ray images into normal and pneumonia cases. The approach focuses on improving early diagnosis, reducing human error, and demonstrating the practical application of machine learning in healthcare.

The project uses a publicly available chest X-ray dataset containing over 5,000 images, consisting of both normal and pneumonia cases. The data undergoes preprocessing steps such as resizing, normalisation, data augmentation, and feature extraction to improve model performance and reduce bias.

A Support Vector Machine (SVM) classifier is implemented alongside Histogram of Oriented Gradients (HOG) feature extraction to detect patterns and abnormalities in X-ray images. 

## Data Description
The dataset used in this study consists of chest X-ray images ethically obtained from Kaggle, an online platform that supports collaboration among researchers, machine learning practitioners, and data scientists on data-driven projects. The dataset includes a structured collection of data organised into training and test folders for model development and evaluation.

## Key Insights
### Skewness Test of Intensity
The skewness distribution was analysed to assess image brightness, contrast levels, and feature characteristics. The skewness values for normal, pneumonia bacteria, and pneumonia virus images were −0.44, −0.67, and −0.35, respectively. Negative skewness indicates that pixel intensity values are concentrated toward brighter regions, with fewer darker pixels.

These results suggest that pneumonia bacteria images contain a higher proportion of bright pixels compared to normal and pneumonia virus images, while normal images show greater brightness than pneumonia virus images.

