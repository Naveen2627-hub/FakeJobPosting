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
In this project, our scope was limited to use only data mining models or not to use NLP models hence we have decided to implement below process:
1. Performed data cleaning by handling data imbalance, outliers, converting categorical variables into binary features using one hot ecoder technique.
2. Identified the 10 most commonly used fradulent words using word frequency technique and converted them into binary features.
3. Implemented feature selection technique, to select most important features using chi square test.
4. Implemented Machine learning models such as Logistic Regression, Decision Trees, Random Forest, Naive Bayes, KNN, XGBoost.
5. Compared the evaluation techniques of all the above models and picked the best performing model which is Random Forest with an
accuracy of 0.8454 and a precision of 0.21.
6. Performed Hyperparameter tuning for Random Forest.



