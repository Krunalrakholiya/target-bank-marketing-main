# Target Marketing for Canadian Bank
## Overview:
In a bid to increase credit balances, Bank "A" is initiating a targeted marketing campaign. The campaign aims to attract existing clients by offering promotional interest rates to encourage deposit balances. The objective is to identify the right set of customers who are most likely to respond positively to the campaign.

## Datasets:
Training Data
Number of Observations: 64,000
Features: 36 variables
Label: 'Target' - Indicates the actual responses from previous campaigns
Testing Data
Number of Observations: 1,480
Features: 36 variables (no labels)
Evaluation Metric:
The success of the model will be evaluated using the ROCAUC Score.

## Attributes:
customer_id:

Unique identifier for each customer.
Balance:

Amount of money owed by the customer on their credit card account.
PreviousCampaignResult:

Categorical variable indicating the customer's response to the last marketing campaign (positive, negative, or no response).
Product1...Product6:

Binary variables indicating ownership of specific bank products.
Transaction1...Transaction9:

Numerical variables representing the amount of money spent or received in the customer's last 9 transactions.
External Accounts 1...External Accounts 7:

Numerical variables representing the number of external accounts the customer has with other financial institutions.
Activity Indicator:

Numerical variable representing the number of activities the customer performed with the bank in a given period.
Regular Interaction Indicator:

Categorical variable representing the frequency of customer interactions with the bank.
CompetitiveRate1 ... CompetitiveRate7:

Numerical variables representing competitive interest rates offered by the bank on different products.
RateBefore:

Numerical variable representing the interest rate the customer had on their products before competitive rates were offered.
ReferenceRate:

Numerical variable representing the negotiated interest rate after considering competitive rates.
## Usage

1. **Clone the repository:**
   ```bash
   https://github.com/jyotsna2411/target-bank-marketing.git```
