# Project Dataset Lab

### Purpose
The repository introduces the dataset being used for the final project, examines it, and does some basic planning and exploratory data analysis. 

### Data
(https://archive.ics.uci.edu/dataset/938/regensburg+pediatric+appendicitis)
This dataset is from the UC Irvine Machine Learning Repository. It contains data donated from a German hospital, in which children with abdominal pain between 2016 and 2021 were admitted. Predictor variables include patient demographics, symptoms, and tests. The binary target is whether or not the child had appendicitis.

### Intended Prediction
To use all 57 features for understanding and predicting child appendicitis. The binary target is "no appendicitis" and "appendicitis." All other variables range from strings to numerical.

### How to Use Notebook
Either load the dataset into the Google Colab link (far left folder icon), or download the notebook and run via VS Code or Jupyter. Do not change any code. Make sure the data file is in the same repository as your notebook. 

### Dependencies
pandas: 2.2.3
matplotlib: 3.10.0
seaborn: 0.13.2
openpyxl: 3.1.5

### Analysis Results
The data is as described in the documentation. To deal with missing values, imputation may be necessary. Various machine learning models like XGboost also can deal with missing values well. I see some unusually small values, however, if babies and newborns were included in this data then it could be correct. I also need to deal with class imbalance issues via SMOTE or other methods. Diagnoses target is correct as it only has 2 possibilities. Therefore, my binary classification is definitely possible.

### Metric and ML Process
My machine learning model will utilize various patient data to predict whether a child has appendicitis or not. This will help find connections to appendicitis and help in its detection sooner. The binary variable will be "appendicitis" or "no appendicitis" predicted from 57 features. For a metric, I believe recall will best capture all children who have appendicitis. Precision will also similarly help us determine how often our model is right. Accuracy will be off due to class imbalance.




