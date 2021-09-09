# Heart-disease-Prediction-using-Data-Science


## A) Domain Background: Overview

Heart disease is major cause of death . According to the Global Burden of Disease, nearly 24.8 per cent of all deaths in India is due to CVDs which is large number number.
## B) Problem Statements
Complete analysis of Heart Disease dataset both visually and statistically to obtain critical observations .
To predict whether a person has a heart disease or not based on the various biological and physical parameters of the body
To make a model having high accuracy and precision and can predict the results with greater confidence.
## C) Datasets and Inputs
## 1. Collecting Data
The data used for training and testing is the Heart Disease downloaded from [kaggle](https://www.kaggle.com/). This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them.The "goal" field refers to the presence of heart disease in the patient.


## 2. Exploratory Data Analysis
It's a clean, easy to understand set of data. However, the meaning of some of the column headers are not obvious. Here's what they mean,

* **age:** The person's age in years
* **sex:** The person's sex (1 = male, 0 = female)
* **cp:** The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
* **trestbps:** The person's resting blood pressure (mm Hg on admission to the hospital)
* **chol:** The person's cholesterol measurement in mg/dl
* **fbs:** The person's fasting blood sugar (&gt; 120 mg/dl, 1 = true; 0 = false)
* **restecg:** Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
* **thalach:** The person's maximum heart rate achieved
* **exang:** Exercise induced angina (1 = yes; 0 = no)
* **ldpeak:** ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot. See more here)
* **slope:** the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
* **ca:** The number of major vessels (0-3)
* **thal:** A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)
* **target:** Heart disease (0 = no, 1 = yes)
## 3. Data Visualization
Now let's see various visual representations of the data to understand more about relationship between various features.

![image](https://github.com/Anjali8356/Heart-disease-Prediction-using-Data-Science/blob/main/Visulaization.png)

## 4. Correlation Matrix
The best way to compare relationship between various features is to look at the correlation matrix between those features.

![image](https://github.com/Anjali8356/Heart-disease-Prediction-using-Data-Science/blob/main/correlation.png)

## 5. Inputs
Here our Model is trained to predict whether a person has a heart disease or not based on the following common features as input:

* age
* gender
* chest pain
* blood pressure
* cholesterol level
* max heart rate
## D) Solution Statements
To make a Linear Regression Model, the problem being a binary classification with very less correlation between features.

## E) Benchmarks
The model will be using a test dataset for benchmarking. The predicted labels will be compared to the original labels to find false positives and false negatives. Number of false positives and false negatives will tell us about the performance of model.

## F) Evaluation Metrics
The model will be using various evaluation metrics such as

* **Accuracy:** which refers to how close a measurement is to the truth value.

* **Precision:** which is how consistent results are when measurements are repeated.



## H) Instructions
Everything has been explained and summarized in the Python Notebook.



