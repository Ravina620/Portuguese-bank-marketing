# Portuguese-bank-marketing
Python, Machine Learning, Pandas,  numpy,  Seaborn , Matplotlib ,  Scikitlearn

**Overview**

This project analyzes a Portuguese bank marketing dataset to understand the factors influencing customer subscription to term deposits. Using data analysis and visualization, the goal is to uncover insights and create predictive models.


**Features**

1. Data cleaning and preprocessing.

2. Exploratory data analysis (EDA) with visualizations.

3. Building predictive models to improve marketing strategies.


**Project Workflow**

**1.Data Collection**: Load the dataset from the CSV file.

**2.Data Preprocessing**: Handle missing values, encode categorical variables, and scale features.

**3.Exploratory Data Analysis (EDA)**: Generate insights with plots and statistical summaries.

**4.Model Training**: Use classification models to predict customer subscriptions.

**5.Evaluation**: Assess model performance using metrics like accuracy, precision, recall, and F1 score.

**Comparison Of ROC AUC score:**

![image](https://github.com/user-attachments/assets/5609b8f1-31d2-4e7f-855c-1a3079462a37)

**Comparison of Recall Score:**

![image](https://github.com/user-attachments/assets/86383377-64a1-47d0-b1d9-6a3c8704b843)


**Conclusion :**

After the analysis we see that our interest is over decreasing the False Negative means the client SUBSCRIBED to term deposit, but the model said he dont which indicates RECALL. So, we conclude that the model with high RECALL score 88.77% would be best suited for the problem statement i.e.,(Random Forest Classifier)
