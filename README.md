# Bank Marketing Campaign Analysis

This project aims to analyze and model the success of a bank marketing campaign. Key insights and findings from the analysis are as follows:

## Data Overview
- The dataset contains client information, including family and education status, financial situation, and previous campaign details.
- The campaign's objective is to sell long-term deposits.
- The dataset is imbalanced, with only 11% of clients subscribing to the deposit.

## Data Exploration
- Categorical features include job, marital status, education, default status, housing, loan, contact, month, day of the week, and previous campaign outcome.
- Numerical features include age, call duration, number of campaign contacts, and economic indicators.
- Significant differences were observed in numerical feature means between successful and unsuccessful marketing campaigns.
- The consumer confidence index's impact on the campaign outcome varies based on the overall economic sentiment.

## Modeling
- Logistic Regression, Random Forest, and Decision Tree models were trained and tested.
- Resampling techniques (oversampling and undersampling) were applied to address class imbalance.
- The Logistic Regression model without resampling achieved the highest accuracy of 91.13%.

This analysis can assist in optimizing future marketing campaigns, understanding client behavior, and improving subscription rates.

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bank-marketing-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd bank-marketing-analysis
   ```

3. View the Jupyter Notebook for detailed code and visualizations:
   ```bash
   jupyter notebook
   ```

Feel free to explore the Jupyter Notebook for a more in-depth analysis.
