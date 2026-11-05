Online Retail Dataset – Data Cleaning Project
Project Overview
This project focuses on identifying and cleaning data quality issues in the Online Retail dataset using Python and Pandas.
Dataset Information
* Dataset: Online Retail
* Source: UCI Machine Learning Repository
* Original Records: 541,909
* Final Records: 536,641
* Total Columns: 8
Tools Used
* Python
* Pandas
* Jupyter Notebook
Data Quality Issues Identified
* Missing Description: 1,454
* Missing CustomerID: 135,080
* Duplicate Records: 5,268
* Descriptions with extra spaces: 113,453
* Negative Quantity: 10,624
* Negative UnitPrice: 2
* Cancelled Invoice Records: 9,288
Data Cleaning Process
1. Removed duplicate records.
2. Replaced missing Description values with "Unknown".
3. Removed extra spaces from Description.
4. Converted CustomerID to nullable integer (Int64).
5. Preserved missing CustomerID values.
6. Retained negative quantities, negative prices and cancelled invoices as potentially valid business records.
Final Validation
* Final Records: 536,641
* Duplicate Records: 0
* Missing Description: 0
* Missing CustomerID: 135,037 (intentionally retained)
Project Files
* data_cleaning.ipynb
* cleaned_online_retail.csv
* README.md
Conclusion
The dataset was successfully inspected, cleaned and validated using Python and Pandas.
