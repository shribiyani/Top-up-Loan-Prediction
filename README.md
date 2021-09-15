# Top-up Loan Up-Sell Prediction

#### What is "**Loan**" & "**Top-Up Loan**"
  - A **loan** is when you **receive the money from a financial institution in exchange for future repayment of the principal, plus interest**. Financial institutions provide loans to the industries, corporates and individuals. The interest received on these loans is one among the main sources of income for the financial institutions.

  - A **top-up loan**, true to its name, is **a facility of availing further funds on an existing loan**. When you have a loan that has already been disbursed and under repayment and if you need more funds then, you can simply avail additional funding on the same loan thereby minimizing time, effort and cost related to applying again.

#### Purpose -


LTFS provides it’s loan services to its customers and is interested in selling more of its Top-up loan services to its existing customers so they have decided **to identify when to pitch a Top-up during the original loan tenure**.  If they correctly **identify the most suitable time to offer a top-up**, this will ultimately lead to more disbursals and can also help them beat competing offerings from other institutions.


To understand this behaviour, LTFS has provided data for its customers containing the information whether that particular customer took the Top-up service and when he took such Top-up service, represented by the target variable Top-up Month.


#### Datasets -
You are provided with two types of information: 

  > 1. **Customer’s Demographics :** The demography table along with the target variable & demographic information contains variables related to Frequency of the loan, Tenure of the loan, Disbursal Amount for a loan & LTV.


  > 2. **Bureau data :**  Bureau data contains the behavioural and transactional attributes of the customers like current balance, Loan Amount, Overdue etc. for various tradelines of a given customer


As a data scientist, LTFS  has tasked you with building a model given the Top-up loan bucket of 128655 customers along with demographic and bureau data, predict the right bucket/period for 14745 customers in the test data.


## Performed Tasks -

- Business Analysis alonge with Problem Analysis,

- Data Preparing - 
  - General Data Analysis,
  - Statistical Aanalysis - Descriptive,
  - Data Visualization,
  - Outlier Investigation

- Baseline : Algorithms Evaluate
  - Train-test Split
  - Initialize Baseline Algorithms to fit Data.
    
- Featuring & Transformation -
  - Feature Engineering - Encoding, NaN Imupation, etc.,  
  - Date Preprocessing & Transformation - Applying Scaling Techniques,
  - Remove Outliers,
  - Feature Selection & Importance
  
- Hyper-Parameter Tunning [Algorithm Tunning] -
  - by Using GridSearchCV
  - by Using RandomSearchCV
  
- Applying Ensemble Techniques -
  - Voting Ensemble,
  - Beyond Voting,
  - Error Correlation,
  - Stacking



[Note - Some files are not able to upload due to size more than 25MB. So ple have look into Google Drive]

Google Drive Link - 
