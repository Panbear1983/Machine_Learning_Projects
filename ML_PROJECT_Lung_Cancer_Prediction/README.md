# Lung Cancer Prediction
We are going to take the following approach:
1. Problem definition
2. Data
3. Evaluation:
- Lung Cancer Level severity According to Sex
- Age vs. Lung Cancer severity level
- Add all the contributing factors together vs. age and plot a scatter graph
4. Features
5. Modelling
6. Experimentation

## 1. Problem Definition
Given clinical parameters about a patient, we want to predict whethere or not they have Lung Cancer?

## 2. Data
The dataset acquired from Kaggle: https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link

## 3. Evaluation
Several plotlibs are introduced to hopefully better visualize the correlations of the values that leads to the levels of lung cancers with various types of graphs for initial evaluation before trying out different models of supervised learning.

## 4. Features
After speaking with the subject matter expert who put together the dataset who has medial knowledge in regards to the correlation of the factors listed in the dataset showned below:
Age: The age of the patient. (Numeric) Gender: The gender of the patient. (Categorical) Air Pollution: The level of air pollution exposure of the patient. (Categorical) Alcohol use: The level of alcohol use of the patient. (Categorical) Dust Allergy: The level of dust allergy of the patient. (Categorical) OccuPational Hazards: The level of occupational hazards of the patient. (Categorical) Genetic Risk: The level of genetic risk of the patient. (Categorical) Chronic Lung Disease: The level of chronic lung disease of the patient. (Categorical) Balanced Diet: The level of balanced diet of the patient. (Categorical) Obesity: The level of obesity of the patient. (Categorical) Smoking: The level of smoking of the patient. (Categorical) Passive Smoker: The level of passive smoker of the patient. (Categorical) Chest Pain: The level of chest pain of the patient. (Categorical) Coughing of Blood: The level of coughing of blood of the patient. (Categorical) Fatigue: The level of fatigue of the patient. (Categorical) Weight Loss: The level of weight loss of the patient. (Categorical) Shortness of Breath: The level of shortness of breath of the patient. (Categorical) Wheezing: The level of wheezing of the patient. (Categorical) Swallowing Difficulty: The level of swallowing difficulty of the patient. (Categorical) Clubbing of Finger Nails: The level of clubbing of finger nails of the patient. (Categorical)

## 5. Modelling
We tried a handful of popular machine learning models to run initial train_test_split procedure like:

LogisticRegression
K-nearest Neighbours Classifier
Random Forest Classifier
Gradient Boosting Machines (GBM)
XGBoost
Support Vector Machines (SVM)
We have also tried to improve upon the models by tweaking the hyperparameter and parameter by hand and cross validate for higher accuracy by looking at the following:

Hyperparameter tuning
Feature importance
Confusion matrix
Cross-validation
Precision
Recall
F1 score
Classification report
Receiver Operating Characteristic (ROC curve)
Area Under the Curve (AUC)
