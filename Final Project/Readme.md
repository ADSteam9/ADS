# Final Project- Insurance Premium Prediction 
This is the final project of INFO7390. The topic is Insurance Premium Prediction with available risk factors.

## http://ec2-52-91-72-142.compute-1.amazonaws.com/
## User name:: admin
## Password:: password

### Our Goal for this project:
- Accurately predict the insurance premium cost for a person knowing all the factors (like smoker or not, no. of children, regin, etc.)


### The dataset consists of:
#### Columns -
- age: age of primary beneficiary
- sex: insurance contractor gender, female, male
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
- charges: Individual medical costs billed by health insurance


### Deployment details:
- Languages: Python
- Pipeline: Luigi/skLearn
- Container: Docker
- Cloud Tool: AWS(Amazon Web Service) EC2/S3


### The Files Description:
- Flask- The folder consists of the app.py file and the templates file
- EDA.ipynb - The file consist of Exploratory Data Analysis done on the dataset
- FeatureEngineering.ipynb - The file consist of feature engineering performed on the region column 
- RegressionModel.ipynb - The file consist of regression models performed on the complete dataset
- kmeans_sklearn.ipnyb - Implementing kmeans algorithm to categorise data into clusters for classifying insurance premiums
- model_pickle.ipnyb - Fitting the models and generating pickled files
- insurance_pipeline.ipnyb - Analyzing various regression models for determining suitable models for prediction
- pipeline_sp.ipnyb - Final pipeline of models used using sklearn and generating error metrics.


### References
- Referred for obesity - https://www.nhlbi.nih.gov/health/educational/lose_wt/BMI/bmicalc.htm
- referred for Kmeans - https://www.youtube.com/watch?v=X3Q6JFl8vjA
- referred for EDA -http://materializecss.com/
-https://www.datasciencebytes.com/bytes/2015/02/24/running-a-flask-app-on-aws-ec2/

## The details of project flow can be found in FinalProjectReport,pdf
