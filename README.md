# Credit-Card-Operations
# Project Overview
The Credit Card Operations Monitoring Dashboard project aims to develop a comprehensive weekly dashboard providing real-time insights into key performance metrics and trends of credit card operations. This dashboard will enable stakeholders to monitor and analyze credit card performance effectively, offering detailed views on transactions, revenue, customer demographics, and more.

![credit card customer report](https://github.com/gayatrikuracha/Credit-Card-Operations-/assets/167384815/983af0bf-347e-472a-a457-27c52a331e7d)

![credit card transaction report](https://github.com/gayatrikuracha/Credit-Card-Operations-/assets/167384815/52213cd2-9f9c-4225-ba32-f786cbe17296)

# Data Source
The primary data sources for this project include CSV files containing raw data on credit card transactions and customer details. These files were imported into a SQL database(PostgreSQL) for structured storage and further analysis.

# Tools Used
- SQL Database(PostgreSQL): For storing and managing the raw data imported from CSV files.
- Power BI: For data transformation, modeling, visualization, and dashboard development.
- DAX (Data Analysis Expressions): For creating measures and calculated columns within Power BI.

# Data Preparation
- Preparing CSV Files: The initial raw data was stored in CSV files.
- Creating Tables in SQL: SQL tables were created to store the data extracted from the CSV files.
- Importing CSV Files into SQL: CSV files were imported into the SQL database using appropriate import commands and procedures.

# Data Transformation
- Import SQL Database to Power BI: The SQL database was connected to Power BI for data extraction.
- Data Transformation in Power BI:
New columns such as total revenue and week number were created in the credit card detail table.
New columns such as age group and income group were created in the customer details table.
- Measures using DAX queries were created, including current week revenue, previous week revenue, and week-over-week revenue percentage.

# Data Modeling
- Creating Relationships: Relationships were established between tables in Power BI to ensure accurate data analysis.
- Calculated Columns and Measures: Various calculated columns and measures were created using DAX to facilitate detailed analysis.

# Data Analysis
- Credit Card Transaction Dashboard:
Key metrics: total revenue, transaction amount, total interest.
Filters: card category, gender, week start date.
- Credit Card Customer Report:
Key metrics: revenue by age group, customer job type, education level.
Filters: gender, week start date, card category.

# Findings
Overall Revenue: $57M YTD.
Total Interest: $8M.
Total Transaction Amount: $46M.
Male Customers Contribution: $31M.
Female Customers Contribution: $26M.
Blue & Silver Credit Cards Contribution: 93% of overall transactions.
Top Contributing States: TX, NY, and CA contributing to 68% of the revenue.
Overall Activation Rate: 57.5%.

# Recommendations
- Marketing Strategy: Focus marketing efforts on states like TX, NY, and CA, as they contribute significantly to the revenue.
- Product Development: Enhance features and benefits for Blue & Silver credit cards since they contribute to the majority of transactions.
- Customer Engagement: Develop targeted campaigns for both male and female customers to balance their contributions.
- Risk Management: Implement strategies to reduce the delinquent rate and increase the activation rate.

# Limitations
- Data Freshness: The analysis is based on weekly data, and real-time updates might not be captured immediately.
- Data Quality: The accuracy of insights depends on the quality and completeness of the raw data imported from CSV files.
- Scope: The dashboard focuses on specific key metrics and may not cover all aspects of credit card operations comprehensively.
- Technical Constraints: Performance of the Power BI dashboard can be affected by the volume of data and complexity of DAX queries.

# References
- Dashboard : [Link](https://github.com/gayatrikuracha/Credit-Card-Operations-/blob/main/Credit%20card%20report.pbix)
  
