# PCOS Detection Using Machine Learning

This repository contains the research paper and associated code for predicting the likelihood of Polycystic Ovarian Syndrome (PCOS) based on specific factors using machine learning and data mining techniques.

## Introduction

Polycystic Ovarian Syndrome (PCOS) is a prevalent endocrine condition among women of reproductive age. Early diagnosis and efficient treatment are crucial to prevent long-term health complications. This research paper focuses on creating a predictive model for efficiently assessing the likelihood of PCOS in females.

## Methodology

To achieve this goal, the following steps were taken:

1. **Data Pre-processing and Cleaning:** The dataset was prepared by cleaning and preprocessing the data to ensure its quality and consistency.

2. **Classification Algorithms:** Five different classification algorithms were employed:
   - Logistic Regression
   - Naive Bayes Classification
   - K-Nearest Neighbors (KNN)
   - Random Forest Classification
   - Support Vector Machine (SVM)

3. **Feature Selection:** The models were trained using relevant variables, including:
   - Follicle Number (Right)
   - Follicle Number (Left)
   - Skin Darkening
   - Hair Growth
   - Weight Gain (Yes/No)
   - Regularity of Menstrual Cycle
   - Fast Food Consumption

4. **Outcome:** The outcome of the model was categorized as "yes" or "no," indicating whether the patient had PCOS or not.

## Results

The findings of this research indicate the following:

- The Support Vector Machine (SVM) algorithm demonstrated the highest level of PCOS prediction accuracy, surpassing the other classification algorithms.

- An analysis of feature significance in predicting the results revealed that "Follicle Number (Right)" was the most crucial feature, followed by "Follicle Number (Left)" and "Weight Gain (Yes/No)."

## Applications

This predictive model has significant potential in the field of healthcare:

- It can assist medical professionals in identifying patients who may be at risk for PCOS, enabling timely interventions and treatments.

- The project underscores the importance of feature selection and algorithm choice in creating precise predictive models, emphasizing the potential of machine learning and data mining in healthcare.

## How to Use

You can access the full research paper and the code in this repository to understand the methodology and findings in detail.



