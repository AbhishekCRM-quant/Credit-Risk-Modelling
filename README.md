# Credit-Risk-Modelling

**Objective**

Credit Risk Modelling for PD, LGD and EAD and their validations

**Project Overview**


This project develops a Probability of Default (PD), Loss Given Defualt and Exposure Modelling

The model uses traditional credit risk modelling techniques including:

Optimal Binning

Weight of Evidence (WOE)

Information Value (IV)

Logistic Regression

AUC / Gini

KS Statistic

PD Calibration


**The target variable is:**


0 = Non-default

1 = Default

Default is defined using delinquent and charged-off loan statuses.

**Methodology**

1. Data Preparation
2. Data cleaning
3. Missing-value treatment
4. Data type conversion
5. Feature engineering
6. Exploratory data analysis
7. Train-Test Split

**The dataset was split into:**

80% Training

20% Testing

**3. Optimal Binning**

Optimal Binning was applied to numerical and categorical variables.

**Information Value (IV) was used to assess predictive strength.**

**4. WOE Transformation**

Variables were transformed using Weight of Evidence (WOE).

Binning was fitted only on the training dataset and the same binning rules were applied to the test dataset.

**5. Logistic Regression**

A logistic regression model was developed using selected WOE-transformed variables.

**6. Model Validation**

The model was evaluated using:

AUC

Gini

KS Statistic

Calibration Plot

Final Model Performance


**Key Features**

The final model included variables such as:

Credit Score

DTI

Delinquencies

Credit Utilization

Annual Income

Credit History

Interest Rate

Employment Years

Recent Inquiries

Loan Amount

Open Accounts

Age


**Conclusion**

The final PD model demonstrated good discrimination and reasonably good calibration on the test dataset.


Model monitoring
Population Stability Index (PSI)
Calibration monitoring
