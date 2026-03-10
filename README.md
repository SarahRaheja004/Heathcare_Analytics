## Heathcare_Analytics

Overview 
This project explores multiple dimensions of healthcare analytics using structured clinical data, operational patient records, healthcare cost data, and unstructured patient feedback text. The goal is to demonstrate how data science techniques can be applied to understand patient outcomes, hospital operations, healthcare expenses, and patient experiences.
The project consists of four Jupyter notebooks, each analyzing a different dataset and answering a different healthcare-related question.

Datasets 

1. Diabetes Hospital Readmission Dataset
Source: Kaggle – Diabetes Dataset
This dataset contains hospital encounter records for diabetic patients from multiple US hospitals. It includes information about patient demographics, medical procedures, medications, diagnoses, and readmission status.
Purpose of analysis:
To identify patterns associated with hospital readmissions and build models to predict whether a patient is likely to be readmitted.
2. Synthetic Healthcare Patient Records Dataset
Source: Kaggle – Synthetic Healthcare Patient Records
This dataset contains simulated hospital patient data including age, gender, BMI, blood pressure, cholesterol levels, diagnoses, admission and discharge dates, treatment cost, and outcome.
Purpose of analysis:
To understand hospital operations, patient flow, and how clinical variables relate to treatment costs and patient outcomes.
3. Medical Insurance Cost Dataset
Source: Kaggle – Medical Cost Personal Dataset
This dataset contains insurance records including age, BMI, number of children, and medical charges.
Purpose of analysis:
To study factors influencing healthcare costs and build predictive models that estimate medical expenses.
4. WebMD Drug Reviews Dataset
Source: Kaggle – WebMD Drug Reviews
This dataset contains patient reviews of medications along with associated medical conditions and ratings.
Purpose of analysis:
To analyze patient experiences using natural language processing techniques and extract sentiment and common themes from healthcare-related text.


Analyses 
1. Hospital Readmission Risk Analysis
This notebook analyzes clinical hospital data to identify factors associated with patient readmissions.
Methods used:
exploratory data analysis
correlation analysis
feature engineering
logistic regression
random forest classification
confusion matrix evaluation
Key insights:
Patients with longer hospital stays tend to have higher readmission risk.
The number of medications prescribed is correlated with readmission probability.
Previous inpatient visits are strong predictors of future readmissions.
Random Forest models capture nonlinear relationships better than logistic regression.
2. Hospital Operations and Patient Outcome Analysis
This notebook investigates operational and clinical patterns in hospital patient records.
Methods used:
exploratory data analysis
demographic analysis
diagnosis frequency analysis
treatment cost distribution
hospital stay duration analysis
regression modeling
Key insights:
Certain diagnoses are associated with longer hospital stays.
Lifestyle risk factors such as smoking and diabetes appear more frequently in some patient groups.
Treatment costs increase with longer hospital stays and more severe diagnoses.
3. Healthcare Cost Analysis
This notebook studies the relationship between patient characteristics and healthcare expenses.
Methods used:
exploratory data analysis
correlation analysis
linear regression
random forest regression
residual analysis
model comparison
Key insights:
Healthcare costs are strongly right-skewed.
Age and BMI show positive relationships with medical expenses.
Random Forest regression captures nonlinear relationships between predictors and costs.
4. Patient Feedback NLP Analysis
This notebook analyzes patient reviews of medications using natural language processing techniques.
Methods used:
text preprocessing
review length analysis
word frequency analysis
word cloud visualization
sentiment analysis using TextBlob
topic modeling using Latent Dirichlet Allocation
sentiment classification using logistic regression
Key insights:
Patient reviews contain strong signals about drug effectiveness and side effects.
Topic modeling reveals recurring themes in medication experiences.
Sentiment analysis allows aggregation of patient experiences across treatments.
NLP provides insights that structured datasets alone cannot capture.


Tools and Technologies
This project was implemented in Python using:
pandas
numpy
seaborn
matplotlib
scikit-learn
TextBlob
wordcloud
All analyses were conducted using Jupyter notebooks.

Skills Demonstrated
This project demonstrates practical experience with:
data cleaning and preprocessing
exploratory data analysis
statistical analysis
data visualization
regression modeling
classification modeling
natural language processing
topic modeling
healthcare data analytics


Future Improvements
Possible extensions include:
1. incorporating time-series hospital admission data
2. building more advanced NLP models using transformers
3. developing dashboards for hospital analytics
4. applying deep learning models for healthcare prediction tasks
