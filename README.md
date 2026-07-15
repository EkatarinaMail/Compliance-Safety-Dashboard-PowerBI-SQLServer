# Compliance-Safety-Dashboard-PowerBI-SQLServer

<img width="880" height="485" alt="Compliance   Safety Dashboard" src="https://github.com/user-attachments/assets/4546cb84-5b7b-4777-bc49-303e8deaaef8" />
*Interactive Compliance & Safety Dashboard built in Power BI*



## Project Overview

This project demonstrates how housing compliance data can be cleaned, structured and visualised to monitor safety risks across a UK housing portfolio.

The dataset is synthetic, but it was designed to look similar to typical social housing compliance exports, including certificate records, properties, repairs, contractors and tenant household information.

I loaded the CSV files into SQL Server, validated record counts, reviewed certificate types and checked raw compliance statuses before building the dashboard in Power BI.

The goal was to create a clear overview of key compliance risks, including action-required records, upcoming renewals, evidence gaps and borough-level risk patterns.



## Key Skills Demonstrated

* **SQL Server Data Loading & Validation:** I imported the synthetic housing compliance CSV files into SQL Server and checked that all tables loaded correctly before reporting.

<img width="245" height="178" alt="sql_record_counts" src="https://github.com/user-attachments/assets/8f5223f9-d4f5-4909-9266-c5265ee2eca3" />
*SQL Server record count validation*


* **Data Quality Review:** I reviewed certificate types and raw compliance statuses to understand the structure of the data and identify inconsistent status values before cleaning.

<img width="1275" height="653" alt="sql_raw_status_check" src="https://github.com/user-attachments/assets/f862eb31-76dc-4e86-8cb9-23c67e6c132a" />
*Reviewing raw compliance statuses in SQL Server*


* **Power Query Cleaning:** I standardised inconsistent compliance status values into a cleaner reporting field called `ComplianceStatusClean`, making the data easier to use in the dashboard.

<img width="1339" height="531" alt="power_query_profiling" src="https://github.com/user-attachments/assets/90426586-8350-4ea9-b59d-a4fad3415cf2" />
*Power Query cleaning and column profiling*


* **Data Modelling:** I structured the Power BI model using fact and dimension tables, connecting compliance and repair records to property and contractor information.

<img width="852" height="496" alt="Data_model" src="https://github.com/user-attachments/assets/f99b2fcb-b1b2-4f19-a8b8-546aa25358b2" />
*Power BI data model with fact and dimension tables*


* **Dashboard Design:** I created an interactive Power BI dashboard with KPI cards, compliance status breakdown, action-required records by borough and filters for certificate type and borough.

<img width="879" height="491" alt="Dashboard_overview" src="https://github.com/user-attachments/assets/604bed66-6991-4661-afc0-f8eeacaa50e6" />
*Compliance & Safety Dashboard Overview*



## Tools Used

Power BI Desktop, Power Query, DAX, SQL Server Management Studio, SQL Server, CSV files.



## Outcome

## Outcome

The final dashboard provides a clear overview of compliance performance across a West London housing portfolio.

It highlights:

* 210 properties monitored
* 1,758 compliance records
* 80 records requiring action
* 117 renewal due records
* 81 evidence gaps
* Borough-level patterns in action-required records

This project demonstrates practical housing data analysis, compliance monitoring, data quality checks and Power BI dashboard design.
