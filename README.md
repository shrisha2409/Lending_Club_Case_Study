# **Lending Club Case Study**

## **Goals of data analysis:**

  Lending Club, a consumer finance marketplace specializing in diverse loan offerings, faces a significant challenge in its loan approval process. The company must carefully assess loan applications to minimize financial losses, particularly those arising from "risky" borrowers.
These financial losses, known as credit losses, occur when borrowers fail to repay their loans or default. In essence, borrowers who are "charged-off" contribute the most substantial losses to the company.
The main goal of this analysis is to help Lending Club reduce credit losses. This challenge presents two key scenarios:

* **Identifying Reliable Borrowers**: It's essential to recognize applicants likely to repay their loans, as they provide profits through interest payments. Failing to approve such applicants results in lost business opportunities.

* **Avoiding Risky Loans**: Conversely, approving loans for applicants who are unlikely to repay and are at high risk of default can lead to significant financial losses for the company.

## **Steps for Analysis:**
- **Load Data:** Import the CSV data into a DataFrame for processing.
- **Clean Data:** Remove any columns that are not necessary for the analysis to streamline the dataset.
- **Data Cleaning:** Address any issues in the required columns, such as handling missing values, correcting data types, or fixing inconsistencies.
- **Verify Distribution:** Examine the distribution of key variables to understand the data better and ensure it is correctly prepared for analysis.
- **Add Risk Flag:** Create a new derived column to flag customers as risky based on predefined criteria.
- **Apply Risk Rules:** Update the risk flag column according to the rules established for identifying risky customers.
 
## **Risk Analysis:**
- In this analysis, we identify risky customers based on the following criteria:
- **Charge-Off Status:** Customers with loans that have been charged off are classified as risky. A charge-off indicates that the loan is unlikely to be repaid and is considered a default.
- **Delinquent Accounts: ** Customers with any delinquent accounts in the past 24 months are considered risky. Delinquency in this timeframe suggests a pattern of financial instability.
- **Public Derogatory Records:** Customers with any public derogatory records in the last 7 years are classified as risky. These records indicate significant financial distress.
- **Collection and Recovery History:** Customers with a history of collections or recoveries are deemed risky. This history reflects past difficulties in repaying debts and indicates a higher likelihood of future issues.


## Technologies Used
- [Python](https://www.python.org/) - version 3.11.4
- [Numpy](https://numpy.org/) - version 1.24.3
- [Pandas](https://pandas.pydata.org/) - version 2.0.3
- [Matplotlib](https://matplotlib.org/) - version 3.7.1 
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2
- Microsoft Power Point
- Jupyter Lab


## Acknowledgements
- Insights and methodologies were derived from peer analyses and community discussions
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Team
- ShivaPrasad Garlapati
- Shrisha Bhat H


