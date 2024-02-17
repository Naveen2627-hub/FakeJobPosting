**Fake Job Posting Prediction**

**Problem Definition**
"Fake Job Posting Prediction" is a data mining project that aims to uncover and flag fake job listings on 
online job boards and recruitment websites. This project will employ a blend of machine learning and web scraping methods to gather and examine data from job postings. 
Machine learning algorithms will be trained to detect patterns in the data that are indicative of fake job postings, 
such as certain keywords or phrases that are commonly used in scam postings. Finally, the system will be 
tested and evaluated to ensure that it can accurately identify and flag fake job postings with a high degree
of accuracy. There are several challenges that may arise in this project such as, Data availability and quality, evolving 
fraud tactics, High class imbalance, False positives, Privacy and security, and keeping the model updated.

**Data Source**
The first step of the project will involve web scraping job postings from various websites to collect a large 
dataset of job postings. We found a dataset in Kaggle in the link below.
https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction?select=fake_job_postings.csv

**Implementation Steps:**
This project focuses on the implementation of data mining techniques to address fraudulent activity detection. The following steps were undertaken:

1. Data Cleaning: The dataset underwent preprocessing to address data imbalances, outliers, and categorical variables were converted into binary features using the one-hot encoding technique.
2. Fraudulent Word Identification: Through word frequency analysis, the top 10 most commonly occurring fraudulent words were identified and converted into binary features.
3. Feature Selection: Employed the chi-square test to select the most significant features for model training.
4. Machine Learning Models: Implemented various machine learning algorithms including Logistic Regression, Decision Trees, Random Forest, Naive Bayes, KNN, and XGBoost.
5. Model Evaluation: The performance of each model was evaluated using standard evaluation metrics. The Random Forest model emerged as the top performer with an accuracy of 0.8454 and a precision of 0.21.
6. Hyperparameter Tuning: Fine-tuned the parameters of the Random Forest model to optimize its performance further.

By adhering to these steps, the project aims to provide an effective solution for fraudulent activity detection while limiting the use of NLP models as per project scope. For detailed implementation and results, refer to the respective sections and documentation within the project repository



