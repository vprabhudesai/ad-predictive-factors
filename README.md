# Project Title: Alzheimer's Disease Prediction Model  (NEED TO UPDATE AFTER TONIGHTS SESSION)

## Project Overview
**Description:**  
This machine learning project focuses on developing a predictive model for Alzheimer's disease using patient data from the [Alzheimers Disease Patient Dataset](https://www.kaggle.com/dsv/8668279) on Kaggle. The model utilizes various health metrics, behavioral indicators, and medical measurements to predict the likelihood of Alzheimer's disease.

**Dataset Description**
The dataset contains 2,149 patient records with 35 features including:
 - Demographic information (age, gender, ethnicity, education level)
 - Health metrics (BMI, blood pressure, cholesterol levels)
 - Behavioral indicators (memory complaints, confusion, behavioral problems)
 - Lifestyle factors (smoking, alcohol consumption, physical activity)
 - Medical assessments (MMSE scores, functional assessments)

**Technologies Used**
 - Python 3.x
 - scikit-learn
 - pandas
 - matplotlib
 - numpy

**Model Architecture**
 - Algorithm: Random Forest Classifier
 - Features: 32 input features (excluding PatientID, DoctorInCharge, and target variable)
 - Target Variable: Binary classification (0: No Alzheimer's, 1: Alzheimer's)

**Inital Model Performance Metrics**
 - Accuracy: 92.6%
 - Precision: 93%
 - Recall: 86%
 - F1-Score: 89%

**Key Findings**

***Most Important Predictors:***
 - Functional Assessment (18.2%)
 - Activities of Daily Living (16.1%)
 - MMSE Score (13.2%)
 - Memory Complaints (7.6%)
 - Behavioral Problems (5%)

***Dataset Characteristics***
 - Imbalanced classes (760 positive cases, 1389 negative cases)
 - Strong correlation between functional assessment scores and diagnosis
 - Significant impact of cognitive measures on prediction accuracy

**Future Improvements**

***Feature Engineering:***
 - Develop composite scores from related features
 - Investigate interaction effects between variables

***Model Optimization:***
 - Implement class balancing techniques
 - Explore other algorithms (XGBoost, LightGBM)
 - Fine-tune hyperparameters further

***Additional Analysis:***

 - Age-group specific performance analysis
 - Risk factor interaction study
 - Feature importance stability analysis


**Model Optimization:**  
- We iteratively improved the model by adjusting hyperparameters.
- A summary of model optimizations and their impacts is available in [document/table].
  

## Future Work & Research
- **Next Steps:**  
  If more time were available, we would further explore time-series analysis to predict the progression of Alzheimer's over time, using historical patient data.
  
- **Research:**  
  We would look into additional data sources, such as genetic or brain imaging data, to improve the model's accuracy.

- **Model Improvements:**  
  Future iterations could focus on implementing more advanced techniques like deep learning for image classification or exploring unsupervised learning approaches to identify hidden patterns in the data.

## Conclusion
This project provided valuable insights into the potential of machine learning to predict Alzheimer's disease risk. The model successfully met the accuracy requirements, and we were able to identify key predictive factors contributing to the disease.

## Contributors
- Vishesh Prabhudesai and Jill Balderson for assistance with data cleaning.
- Vishesh Prabhudesai and Jill Balderson for help with model optimization.
- Vishesh Prabhudesai and Jill Balderson for visualizations and final presentation design.



## Dataset Citation
@misc{rabie_el_kharoua_2024,
title={Alzheimer's Disease Dataset},
url={https://www.kaggle.com/dsv/8668279},
DOI={10.34740/KAGGLE/DSV/8668279},
publisher={Kaggle},
author={Rabie El Kharoua},
year={2024}
}

