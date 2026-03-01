# MATLAB-Pneumonia-Detection-from-Chest-X-ray
This project develops a machine learning system for automated pneumonia detection from chest X-ray images. The aim is to improve diagnostic accuracy, support medical professionals, and enable faster clinical decision-making through intelligent image classification.

## Overview
The system applies image preprocessing, feature extraction, and machine learning techniques to classify chest X-ray images into normal and pneumonia cases. The approach focuses on improving early diagnosis, reducing human error, and demonstrating the practical application of machine learning in healthcare.

The project uses a publicly available chest X-ray dataset containing over 5,000 images, consisting of both normal and pneumonia cases. The data undergoes preprocessing steps such as resizing, normalisation, data augmentation, and feature extraction to improve model performance and reduce bias.

A Support Vector Machine (SVM) classifier is implemented alongside Histogram of Oriented Gradients (HOG) feature extraction to detect patterns and abnormalities in X-ray images. 

## Data Description
The dataset used in this study consists of chest X-ray images ethically obtained from Kaggle, an online platform that supports collaboration among researchers, machine learning practitioners, and data scientists on data-driven projects. The dataset includes a structured collection of data organised into training and test folders for model development and evaluation.

### Technologies Used
- **MATLAB**

## Key Insights
### Skewness Test of Intensity
The skewness distribution was analysed to assess image brightness, contrast levels, and feature characteristics. The skewness values for normal, pneumonia bacteria, and pneumonia virus images were −0.44, −0.67, and −0.35, respectively. Negative skewness indicates that pixel intensity values are concentrated toward brighter regions, with fewer darker pixels.

These results suggest that pneumonia bacteria images contain a higher proportion of bright pixels compared to normal and pneumonia virus images, while normal images show greater brightness than pneumonia virus images.

                           
<image src="Images/skewness1.png" width=250>  <image src="Images/SkewnessIM.png" width=250>  <image src="Images/SkewnessVir.png" width=250> 

### Support Vector Machine
The Support Vector Machine (SVM) model demonstrated strong classification performance in distinguishing between normal and pneumonia chest X-ray images.

The confusion matrix shows 83 correct predictions and 6 misclassifications, indicating high model reliability. The model achieved a precision of 0.932, recall of 0.934, and an F1-score of 0.933, reflecting balanced performance in detecting both positive and negative cases.

<image src="Images/Screenshot.png" width=300> 


### Conclusion
This project demonstrates the effectiveness of machine learning techniques for automated pneumonia detection from chest X-ray images. Through image preprocessing, feature extraction, and SVM and HOG-based classification, the study shows that machine learning can improve diagnostic accuracy and support faster medical decision-making.
