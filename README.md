# telecomchurnprediction
ABSTRACT
For telecommunications businesses, customer churn, or the loss ofconsumers to rivals, is a serious problem because it affects their revenue and
profitability. Thus, preserving client loyalty and corporate success depend onprecisely forecasting and reducing turnover. In this research, we provide a
machine learning method for anticipating telecom churn that makes use of pastcustomer data and sophisticated analytical methods. There are various stages to
the suggested strategy. To assure data quality and consistency, a large datasetcontaining customer information, call usage, billing information and service
usage is first gathered. To understand the data and find potential churnindicators, exploratory data analysis (EDA) is carried out. To create pertinent
features that reflect the customer's behavior, preferences, and interactions withthe telecom, feature engineering techniques are used.Predictive models are then
developed using a variety of machine learning algorithms, such as logisticregression, decision trees, random forests and neutral networks. The model's
success in forecasting churn is measured using metrics including accuracy, precision, recall, F1-score, and area under the receiver operating characteristic
(ROC) curve, which are trained using historical data.Additionally, to find themost important features for predicting churn and enhance model performance, feature selection approaches such the chi-square test, mutual information, and recursive feature 

DATASET DESCRIPTION
The dataset used in the telecommunication churn prediction is the ChurnDataset. The Churn Dataset is a popular dataset that contains information about
7,000 people. This dataset was taken from a popular website which is kaggle . The dataset contains information on various attributes like customerID, gender- whether the customer is a male or a female,SeniorCitizen - whether thecustomer is a senior citizen or not (1, 0), Partner - whether the customer has a
partner or not (Yes, No), Dependents - whether the customer has dependents ornot (Yes, No), Tenure - number of months the customer has stayed with the
company, PhoneService - whether the customer has a phone service or not (Yes, No), MultipleLines - whether the customer has multiple lines or not (Yes, No, No phone service), InternetService - customer’s internet service provider (DSL, Fiber optic, No), OnlineSecurity - whether the customer has online security ornot (Yes, No, No internet service), OnlineBackup - whether the customer hasonline backup or not (Yes, No, No internet service), DeviceProtection - whether
the customer has device protection or not (Yes, No, No internet service), TechSupport - whether the customer has techsupport or not (Yes, No, No
internet service), StreamingTV - whether the customer has streaming TV or not(Yes, No, No internet service), StreamingMovies - whether the customer has
streaming movies or not (Yes, No, No internet service), Contract - after howmuch time the contract gets updated, PaperlessBilling - whether the customer
billing is paperlessbilling or not (Yes, No), PaymentMethod, - what is thepayment method done by customer (Electronic check, Mailed check, Bank
transfer or credit card), MonthlyCharges - what are the monthly charges thatcustomer has to pay, TotalCharges - what are the total charges that customer has
to pay and Churn - whether the customer has churning behaviour or not (Yes or No). Here, customerID is removed because each customer has a unique id. Churn
column is the target variable and remaining all other columns are features. Thisdataset is already preprocessed and it doesn't have any null values or outliers. This dataset is now used to train different models and predict customer churn behavior and develop strategies to reduce customer churn and improve customer
retention in a business or service provider’s operations.
