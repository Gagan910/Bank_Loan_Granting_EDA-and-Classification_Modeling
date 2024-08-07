# Bank Loan Granting: EDA and Classification Modeling

This project involves an exploratory data analysis (EDA) and classification modeling for predicting bank loan granting. The project includes detailed steps for data cleaning, visualization, and building classification models.

## Table of Contents
1. [Libraries and Dataset](#libraries-and-dataset)
2. [Data Cleaning](#data-cleaning)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Classification Modeling](#classification-modeling)
5. [Results](#results)
6. [Conclusion](#conclusion)

## Libraries and Dataset
The notebook begins with importing necessary libraries and reading the dataset. The dataset contains 5000 samples with 14 columns, including customer demographics, account information, and whether the customer was granted a loan.

### Features:
- **ID**: Customer ID
- **Age**: Age of the customer
- **Experience**: Number of years of experience
- **Income**: Annual earnings of the customer
- **ZIP Code**: Customer's location postal code
- **Family**: Number of people in the customer's family
- **CCAvg**: Average monthly credit card spending
- **Education**: Level of education (Undergraduate, Graduate, Professional)
- **Mortgage**: Value of the customer's mortgage
- **Securities Account**: Whether the customer has a securities account
- **CD Account**: Whether the customer has a Certificate of Deposit (CD) account
- **Online**: Whether the customer uses online banking services
- **CreditCard**: Whether the customer uses the bank's credit card

### Target:
- **Personal Loan**: Whether the customer was granted a loan

## Data Cleaning
- Checking for missing values and ensuring there are none.
- Converting necessary columns to numeric types.
- Checking for and handling duplicated data.
- Correcting any anomalous values in the dataset (e.g., negative values in experience).

## Exploratory Data Analysis (EDA)
- **Data Information**: Summary statistics and insights about the dataset.
- **Dependency Analysis**: Relationships between features and the target variable.
    - Continuous features such as Income, CCAvg, and Mortgage.
    - Discrete features such as CD Account.
    - Visualization of dependencies using 3D plots and map plots.

## Classification Modeling
- Building and evaluating classification models to predict whether a customer will be granted a loan.
- Models include logistic regression, decision trees, and other machine learning algorithms.
- Evaluation metrics to assess model performance.

## Results
- Summary of findings from the EDA.
- Performance metrics of the classification models.
- Key insights and patterns identified in the data.

## Conclusion
- Final thoughts on the analysis and modeling.
- Potential areas for further research or improvement.

---

### How to Use This Repository
1. Clone the repository:
   ```bash
   git clone [https://github.com/Gagan910/Bank_Loan_Granting_EDA-and-Classification_Modeling]
