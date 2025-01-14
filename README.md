# Project Title: Alzheimer's Disease Prediction Model  (DRAFT.. EDIT WITH MORE ACCURATE/UP TO DATE INFO AS WE MOVE THROUGH PROJECT)

## Project Overview
**Description:**  
In this project, we will develop a machine learning classification model to predict Alzheimer's disease progression in patients based on various factors. Using an Alzheimer's Disease patient dataset from Kaggle (Full Citation below in ReadMe file), we aim to identify the predictive factors that are most strongly associated with the likelihood of Alzheimer's disease. Our model will be built using Scikit-learn, and we will evaluate its performance using a variety of metrics.

**Objective:**  
- Build a machine learning model that can predict the likelihood of Alzheimer's disease in patients.
- Evaluate and optimize the model's performance to ensure it achieves at least 75% classification accuracy.
- Leverage various Python tools, including Pandas, Scikit-learn, and Matplotlib, to analyze and visualize the data.

**Key Features:**
- Data exploration and preprocessing (cleaning, transformation, scaling)
- Model selection and evaluation using metrics like accuracy and R-squared.
- Visualization of key factors influencing Alzheimer's prediction.

## Data Collection and Preparation
**Dataset Overview:**  
- The dataset used contains information on patients with Alzheimer’s disease, including demographic data, clinical measurements, and medical history.
- The dataset has over 500 records, which are used for training and testing the model.

**Data Cleaning & Transformation:**  
- The dataset did not actually require any processing for missing values, outliers, and duplicates. We did remove two irrelevant columns, including DoctorInCharge and PatientID.
- We performed feature engineering to extract important features relevant to Alzheimer's disease prediction.
- Data was split into training and testing sets for model evaluation.

**Tools Used:**
- **Pandas:** For data manipulation and cleaning.
- **Matplotlib & Pandas Plotting:** For data visualization.
- **Scikit-learn:** For machine learning model implementation and evaluation.

## Model Implementation
**Model Selection:**  
- We selected a classification model (Random Forest, Decision Tree) to predict the likelihood of Alzheimer's disease.
- The model was trained using the processed dataset and evaluated using various metrics.

**Model Training & Evaluation:**
- We split the data into training and testing sets (80/20 split).
- The model achieved an accuracy of 92.3% on the test set, exceeding the 75% indicated in the project requirements.

**Evaluation Metrics:**
- Accuracy: [X]%
- Precision, Recall, F1-Score: [X]%
- ROC Curve: ![Insert Graph]

**Model Optimization:**  
- We iteratively improved the model by adjusting hyperparameters.
- A summary of model optimizations and their impacts is available in [document/table].
  
**Tools Used:**
- **Scikit-learn:** For training and evaluating the model.
- **Matplotlib/Seaborn:** For visualizing model performance.

## GitHub Repository Structure

/project-root ├── /data └── cleaned_data.csv ├── /notebooks └── data_exploration.ipynb ├── /scripts └── train_model.py ├── README.md └── requirements.txt

**.gitignore:**  
- Contains the list of files to exclude from version control, such as data files, temporary files, etc.

## Future Work & Research
- **Next Steps:**  
  If more time were available, we would further explore time-series analysis to predict the progression of Alzheimer's over time, using historical patient data.
  
- **Research:**  
  We would look into additional data sources, such as genetic or brain imaging data, to improve the model's accuracy.

- **Model Improvements:**  
  Future iterations could focus on implementing more advanced techniques like deep learning for image classification or exploring unsupervised learning approaches to identify hidden patterns in the data.

## Conclusion
This project provided valuable insights into the potential of machine learning to predict Alzheimer's disease risk. The model successfully met the accuracy requirements, and we were able to identify key predictive factors contributing to the disease.

## Acknowledgments
- Vishesh Prabhudesai and Jill Balderson for assistance with data cleaning.
- Vishesh Prabhudesai and Jill Balderson for help with model optimization.
- Vishesh Prabhudesai and Jill Balderson for visualizations and final presentation design.

## Requirements
To run the project locally, ensure the following dependencies are installed:
- Python 3.x
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebooks (for exploration)

## Dataset Citation
@misc{rabie_el_kharoua_2024,
title={Alzheimer's Disease Dataset},
url={https://www.kaggle.com/dsv/8668279},
DOI={10.34740/KAGGLE/DSV/8668279},
publisher={Kaggle},
author={Rabie El Kharoua},
year={2024}
}

