<ins>**Background**</ins>

The mean cost of living in the United States for a family of four is approximately $7,083 per month, which equates to $85,000 per year (Upwardli, 2023). While this number may fluctuate due to location, it is important for parents to be financially capable of supporting themselves and their families. Stack Overflow posted survey results from their 2022 Developer Survey on Kaggle, which contains every recorded response from individuals with technical skill sets (Elgazar, 2023). This provided the opportunity to analyze and model dependent variables to predict if these technical individuals were able to support the mean cost of living for a family of four in the United States.

Within the 2022 Developer Survey, there are 79 attributes and 73,268 observations from respondents from around the world. For the purpose of this study, total compensation (CompTotal) will represent the independent variable. Years of professional programming (YearsCodePro), education level (EdLevel), remote work status (RemoteWork), and employer size (OrgSize) will represent dependent variables for the study.
<br/>
<br/>

<ins>**Purpose**</ins>

The main purpose of this project was to practice data mining algorithms based on the Kaggle data set. A threshold of $85,000 was set in order to accurartely run data mining models that assess if an individual makes $85,000 or more based on their number of years professionally programming, education level, work location (fully remote, hybrid, and fully-inperson), and organization size. The following models were created during this project:

- Decision Tree
- K-Nearest Neighbor
- Naive Bayes
- Logistic Regression
- Neural Networks
- Random Forest
- Support Vector Machine (SVM)
<br/>

<ins>**Results**</ins>

To evaluate the results for this project it is necessary to determine a baseline model. Identifying all true positives was vitally important for this study. The data presents that 82.6% of respondents have a total compensation above $85,000. Thus, the baseline model will predict all true positives of respondents above the defined threshold, resulting in an accuracy of 82.6%.

As this is a classification problem with a binary target variable, the metrics chosen to compare the models are accuracy, precision, recall, F1-score, and AUC.  For every model a contingency table is created to compare the predicted values with true and predicted results equal to or above $85,000 and below $85,000. 

All models present similar metrics. For example, they all have an accuracy close to 84% (see Table 1). This is a good accuracy, but the difference is very small compared to the baseline model (83%). This resulted in the data mining models having more accurate predictions by 1%.


<br/><br/>
<ins>**Link to Kaggle**</ins>

https://www.kaggle.com/datasets/ebrahimelgazar/stack-overflow-2022-developer-survey?select=survey_results_public.csv 
