# GENDER PREDICTION USING DENTAL MEASUREMENTS

## Project Overview
This project aims to predict gender based on dental measurements using machine learning techniques. The primary objective is to develop a robust model capable of accurately classifying gender by leveraging dental features, which may exhibit sexual dimorphism. The dataset, derived from dental records, includes various measurements such as tooth dimensions and jaw characteristics. By applying advanced classification algorithms, including Random Forest, Logistic Regression, Decision Trees, and XGBoost, the project seeks to identify the most effective model for gender prediction and evaluate its performance. The significance of this study lies in its potential to assist forensic dentistry and clinical applications by providing a non-invasive method for gender identification.

## Results:
* XGBoost outperformed other models with an accuracy of 90.9% and ROC AUC of 0.91. Random Forest followed with 89.1% accuracy. Logistic Regression, while interpretable, lagged in performance. The models were effective at identifying both genders, with slightly higher recall for males in Random Forest and for females in Logistic Regression.
* Key features contributing to prediction included intercanine distances and canine widths from both intraoral and cast measurements. Cross-validation further confirmed the robustness of the models with a mean accuracy of 79.6% for Random Forest.

## Author
Leela Josna Kona

## Dataset and model
Dentistry Dataset.csv
A structured dataset with 1,100 records including:
    •	Intercanine distance
    •	Canine width
    •	Canine index
The target variable is Gender (Male/Female), which will be encoded numerically for modeling.
    •	Target Variable: Gender (Male/Female)
    •	Independent Variables:
        o	Inter-canine distances (intraoral and casts)
        o	Right and left canine casts
        o	Other dental measurements
    •	Additional Attributes: Sample ID, SL No., and Age

## Libraries Used
* Pandas, Numpy
* Matplotlib, Seaborn
*	Scikit-learn
*	XGBoost
* IDE: Jupyter Notebook

## Future work
Future directions include:
*	Incorporating Radiographic Images: Add dental X-rays to leverage image-based features.
*	Deep Learning Integration: Utilize Convolutional Neural Networks (CNNs) in TensorFlow for automatic feature extraction from images.
*	Larger Dataset: Improve model generalizability by increasing sample size and diversity.
*	Clinical Application: Build a tool for gender estimation in forensic or dental practice environments.

