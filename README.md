# Loan Distributement Data Project

<h1>Overview</h1>

This Power BI project provides an interactive dashboard to analyze loan disbursements, loan officer performance, and portfolio risk. The dashboard enables financial institutions to gain insights into loan trends and portfolio health.

<h2>Features</h2>

Monthly Loan Disbursements: Displays total loan disbursements in EUR over the last 6 months using principal_amount_eur.

Loan Officer Performance: Visualizes the count of loans disbursed per loan officer for the last month and the total disbursed loan volume.

Portfolio at Risk (PAR): Uses a KPI visualization to show the proportion of outstanding loan amounts with overdue days greater than 30.

Filter Options: Allows users to filter data by branch_key, product, and loan_officer.

<h2>Data Fields Used</h2>

principal_amount_eur: Represents the total loan disbursed.

principal_amount_outstanding_eur: Represents the total outstanding loan amount.

overdue_days: Used to determine overdue loans for PAR calculation.

loan_officer: Categorizes disbursement by officer.

branch_key and product: Provide breakdown filtering.
