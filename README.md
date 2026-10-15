# Final Project

### Purpose
The repository introduces a checkpoint notebook for the final project. It is incomplete but a work in progress.
### Data
(https://archive.ics.uci.edu/dataset/938/regensburg+pediatric+appendicitis)
This dataset is from the UC Irvine Machine Learning Repository. It contains data donated from a German hospital, in which children with abdominal pain between 2016 and 2021 were admitted. Predictor variables include patient demographics, symptoms, and tests. The binary target is whether or not the child had appendicitis.

### Intended Prediction
To use all 57 features for understanding and predicting child appendicitis. The binary target is "no appendicitis" and "appendicitis." All other variables range from strings to numerical.

### How to Use Notebook
Either load the dataset into the Google Colab link (far left folder icon), or download the notebook and run via VS Code or Jupyter. Do not change any code. Make sure the data file is in the same repository as your notebook. 

### Dependencies
TBD when final notebook produced

### Analysis
The data was loaded, cleaned, explored, preprocessed, and trained on three supervised machine learning models with a final result table of all metrics. 5 advanced implementations were used to make the pipeline more robust. The details are in the top of the notebook.

### Metric and ML Process
My machine learning model utilizes various patient data to predict whether a child has appendicitis or not. This will help find connections to appendicitis and help in its detection sooner. The binary variable "appendicitis" or "no appendicitis" is predicted from 57 features. For a metric, I believe recall will best capture all children who have appendicitis. imbalance.




