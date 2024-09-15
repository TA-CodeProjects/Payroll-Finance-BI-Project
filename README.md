# Payroll Finance -  BI Project
The project provide a BI Solution for AdWorks IT outsource company.
![image](https://github.com/user-attachments/assets/f6c37fe9-7e66-4d57-9d32-93bf4718732c)

![image](https://github.com/user-attachments/assets/1e8bccf1-bc42-4ed7-a0a2-1e086a3d2a18)

![image](https://github.com/user-attachments/assets/3a5f6315-6c4a-4108-9364-9c23f564d26a)

![image](https://github.com/user-attachments/assets/b712492d-e2fb-46ef-ab18-5bd0c8d11608)

![image](https://github.com/user-attachments/assets/90c653af-7c21-401e-9df5-f914c012a6bc)


## Project Overview
### Project Specifications:
Planning the data mart and reports, including crafting essential documents such as the [ERD](https://github.com/TA-CodeProjects/Payroll-Finance-BI-Project/blob/main/ERD.png) and [Source-to-Target Mapping](https://github.com/TA-CodeProjects/Payroll-Finance-BI-Project/blob/main/S2T%20Mapping.xlsx)

### Data Mart Development: 
SSIS is used for the ETL process to load OLTP data from the adventurework2019 database, transform it, and load it to the final Data Mart tables.
Data quality assurance tests were conducted throughout this process to maintain data integrity. 
The resulting data mart comprises 2 fact table, 4 dimension tables.

### Power BI Reports:
This phase involved creating additional tables, calculated columns, and measures using DAX to support the envisioned visualizations and, subsequently, proceeding to craft and design the visualizations.
1 Executive Dashboard, 2 analysis reports were created: Employee Salary Analysis and a Customers Billing Analysis and 2 details report for drilldown: Employee Details Report and Customer Details Report.

## Repository Contents
* [BI System Specifications Document.pdf](https://github.com/TA-CodeProjects/Payroll-Finance-BI-Project/blob/main/Finance%20Payroll%20BI%20Project.pdf): Detailed project specifications.

* [ERD.PNG](https://github.com/TA-CodeProjects/Payroll-Finance-BI-Project/blob/main/ERD.png): Visual representation of the database schema, illustrating entity relationships.

* [S2T Mapping.xlsx](https://github.com/TA-CodeProjects/Payroll-Finance-BI-Project/blob/main/S2T%20Mapping.xlsx): Document detailing the transformation and loading process of source system data into the data mart.

* [Dashboard.pbix](https://github.com/TA-CodeProjects/Payroll-Finance-BI-Project/blob/main/Finance%20payroll.pbix): The Power BI file containing the developed reports and visualizations.
