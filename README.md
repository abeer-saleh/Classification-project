# Project 03: Classification project
 
<p align="center">
  <img width="200" src="http://customer-churn.com/assets/img/logo.png" alt="logo">
</p>


#### Name: Abeer AlRuwayti
#### Email: abeeralruwaitea@gmail.com

# Data Description:

In this project, we obtaind our dataset from (https://www.kaggle.com/blastchar/telco-customer-churn)  <br />
Each row represents a customer, each column contains customer’s attributes described on the table below <br />
The raw data contains 7043 rows (customers) and 21 columns (features) <br />
The “Churn” column is our target <br />

 |Features|Description                                                                         |  Type |
 |-------|--------------------------------------------------------------------------------------|--- |
 |                                                                                                    |
 | customerID | customer identification number                                                | Object |
 | Gender | Whether the customer is a male or a female                                         | Object |
 | SeniorCitizen | Whether the customer is a senior citizen or not (1, 0)                      | int64 | 
 | Partner | Whether the customer has a partner or not (Yes, No)                               | Object |
 | Dependents | Whether the customer has dependents or not (Yes, No)                           | Object |
 | tenure | Number of months the customer has stayed with the company                          | int64 |
 | PhoneService | Whether the customer has a phone service or not (Yes, No)                    | Object |
 | MultipleLines | Whether the customer has multiple lines or not (Yes, No, No phone service)     | Object |
 | InternetService | Customer’s internet service provider (DSL, Fiber optic, No)                  | Object |
 | OnlineSecurity | Whether the customer has online security or not (Yes, No, No internet service)| Object  |
 | OnlineBackup | Whether the customer has online backup or not (Yes, No, No internet service)| Object  |
 | DeviceProtection | Whether the customer has device protection or not (Yes, No, No internet service)| Object  |
 | TechSupport | Whether the customer has tech support or not (Yes, No, No internet service)| Object  |
 | StreamingTV | Whether the customer has streaming TV or not (Yes, No, No internet service)| Object  |
 | StreamingMovies |Whether the customer has streaming movies or not (Yes, No, No internet service)| Object  |
 | Contract | The contract term of the customer (Month-to-month, One year, Two year)| Object  |
 | PaperlessBilling | Whether the customer has paperless billing or not (Yes, No)| Object  |
 | PaymentMethod | The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))| Object  |
 | MonthlyCharges | The amount charged to the customer monthly           | float64  |
 | TotalCharges | The total amount charged to the customer           | Object  |
 | Churn | Whether the customer churned or not (Yes or No)           | Object  |

 
# Tools:

#### Technologies

* Python
* Jupyter Notebook

#### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn 
* Sklearn
* Pandas Profiling
