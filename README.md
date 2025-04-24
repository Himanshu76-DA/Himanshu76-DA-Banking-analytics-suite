# Banking Risk Analysis & Dashboard Project

This project focuses on analyzing a banking dataset to extract key insights and build a logical risk-weighting system. The final output includes an interactive dashboard created using Power BI to visualize important trends related to clients, financial activity, and loan risk.

---

## Files Included
- `Banking.csv` – Raw dataset used for analysis
- `Bank_Analysis_JUP.ipynb` – Jupyter Notebook with full data cleaning, EDA, and risk logic
- `Banking Analysis.pbit` – Power BI dashboard file
- `Banking` – Folder containing dashboard preview images

---

## Key Objectives
- Analyze client and financial patterns in the dataset
- Create a more accurate and logical risk weighting column
- Identify risk-prone customers using data-driven logic
- Visualize key insights through an interactive dashboard

---

## Tools & Libraries
- Python (pandas, matplotlib, seaborn)
- Power BI for Dashboard
- Jupyter Notebook

---

## Dashboard Preview

![Dashboard Preview](Banking/screenshots/dashboard_preview.png)

---

## Project Insights

- **High Loan, Low Income = High Risk**  
  Customers with high loan amounts but low estimated income generally fall into Risk Level 4 or 5, indicating a high probability of default unless recovery strategies (e.g., asset seizure) are applied.

- **Strong Correlation Between Deposit Types**  
  A positive correlation exists between bank deposits, savings, and checking accounts, suggesting that financially stable clients diversify their funds across different accounts.

- **Estimated Income Drives Saving Habits**  
  Estimated income shows a moderate positive correlation with annuity savings, implying that high-income clients also prioritize long-term financial planning.

- **Account Balances Support Risk Decisions**  
  Clients with high total balances tend to fall into lower risk categories. Account balances act as a financial cushion during defaults.

- **Properties Owned Reduce Risk**  
  Clients who own multiple properties typically fall into low- to mid-risk levels. Property ownership offers security and aids in recovery planning.

- **Business Lending and Risk Trends**  
  Business lending is correlated with higher loan amounts and risk weights, showing that business clients often carry larger and riskier loans.

- **Credit Card Usage Patterns**  
  Clients with high credit card balances tend to fall in medium-to-high risk tiers. There's also a moderate link between credit card and loan balances.

- **Gender-Based Risk Differences**  
  Male clients are slightly more represented in higher risk categories. Female clients generally maintain better balance-to-loan ratios, indicating more stable financial behavior.

- **Year of Joining vs Risk Level**  
  Older clients (joined before 2015) tend to have higher savings and lower risk levels. Clients who joined after 2020 show more variability in income and loan metrics.

- **Property Ownership as Recovery Indicator**  
  Clients owning multiple properties rarely appear in high-risk tiers. Property count is a strong indicator for risk mitigation and recovery confidence.

- **European Clients Dominate Loan Distribution**  
  European clients hold the largest share of total loans (1.93B), indicating a strong loan portfolio. This could guide strategies for expansion among other nationalities.

- **Risk Weighting Impact on Loans**  
  Most loans are concentrated in Risk Categories 1 and 2 (totaling 2.95B), while higher risk tiers (4 & 5) have lower loan volumes — reflecting a conservative lending approach.

- **Loyalty Class Reflects in Saving Patterns**  
  Jade class customers hold the highest savings account balance (33.5M), nearly 4x that of Platinum class (7.9M), suggesting loyalty programs may influence saving behavior.

- **Customer Distribution by Risk Weight**  
  Over 69% of customers fall under Risk Categories 1 and 2, indicating a risk-averse customer base — potentially translating to lower loan defaults.

- **Income Disparity Across Nationalities**  
  Europeans lead in income (229M), followed by Asians (129M). This variation may inform targeted offerings in credit and investment products.

---

## Contact

If you want to discuss or collaborate on financial analytics projects, feel free to reach out:

**Himanshu**  
Email: [himanshujanghu76@gmail.com](mailto:himanshujanghu76@gmail.com)
