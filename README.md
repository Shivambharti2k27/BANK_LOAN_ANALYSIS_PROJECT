# 🏦 Bank Loan Analysis: SQL & Power BI Project

 **📌 Project Overview**
1. This project is designed to provide a deep-dive analysis of bank loan data to monitor lending health and borrower behaviour.
2. The primary goal is to track key lending metrics and visualise the distribution of "Good Loans" versus "Bad Loans."
3. The project uses SQL for robust data querying and Power BI for high-level executive dashboards.


 **🎯 KPI Requirements**
1. **Total Loan Applications**: Tracking the total volume of loan requests received.
2. **Total Funded Amount**: Monitoring the total capital disbursed to borrowers.
3. **Total Amount Received**: Tracking the total repayment (including interest and fees) to assess cash flow.
4. **Average Interest Rate**: Calculating the average cost of borrowing across all loans.
5. **Average Debt-to-Income (DTI)**: Assessing the financial health of borrowers by measuring their average DTI ratio.


 **📊 Performance Categorization**
1. **Good Loan Analysis**:
1. **Good Loan Application Percentage**: Loans with a status of 'Fully Paid' or 'Current'.
2. **Good Loan Funded Amount**: Total capital allocated to reliable borrowers.
3. **Good Loan Total Received Amount**: Total money recovered from healthy loans.


 **Bad Loan Analysis**:
1. **Bad Loan Application Percentage**: Loans with a status of 'Charged Off'.
2. **Bad Loan Funded Amount**: Total capital at risk or lost.
3. **Bad Loan Total Received Amount**: Amount recovered from defaulted accounts before charge-off.




 **📈 Visualizations & Reports**
1. **Monthly Trends (Line Chart)**: To identify seasonality and peaks in loan applications.
2. **Regional Analysis (Filled Map)**: Visualizing loan distribution across different states.
3. **Loan Term Analysis (Doughnut Chart)**: Understanding the preference between short-term (36 months) and long-term (60 months) loans.
4. **Employee Length Analysis (Bar Chart)**: Correlating employment stability with loan volume.
5. **Loan Purpose Breakdown (Bar Chart)**: Categorising the primary reasons borrowers seek funding (e.g., debt consolidation, home improvement).


 **🛠 Tools & Technologies Used**
1. **SQL**: Used for data cleaning and complex KPI calculations (refer to `Bank Loan SQL Queries.pdf`).
2. **Power BI**: Used for building the interactive `.pbix` dashboard.
3. **Excel/CSV**: Source data containing transactional loan records.


 **📂 How to Use**
1. **Database Setup**: Import the `financial_loan.csv` file into your SQL Server.
2. **SQL Analysis**: Run the provided SQL scripts to generate summary tables and verify KPI accuracy.
3. **Power BI**: Open the `Lelin power bi Bank analysis.pbix` file to explore the interactive visualisations and filter data by grade, purpose, or state.



---

**Would you like me to add a section specifically listing the "Top 5 States by Loan Volume" based on the data in your CSV?**
