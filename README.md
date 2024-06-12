# World Report Fabric_Data_Engineering_Projects

![Slide1](https://github.com/Abdur-RasheedAde/Fabric_Data_Engineering_Projects/blob/main/DEArchitecture.png)

##  Project Overview
This is a complete End-to-End Fabric Data Engineering project where PDF, Excel Power Query, Python Beautiful Soup, SQL, Pyspark, lake House and Power BI are explored. The project ingest data from multiple sources like the web, pdf and csv into the Fabric Lake house, created a robust Data pipeline in Fabric for the ETL process and stored the data in a LakeHouse where Visualization Report got it's data source. 

## Data Source:
A pizza_store _data is used which was ingested as a csv file into the SQL server Database;  
* The Pizza_Store Data is here 👉 [Download Pizza data_here](https://github.com/Abdur-RasheedAde/Complete_Azure_DE_Pizza_Project/blob/main/pizza_sales.csv)

## DE Technical Skills:
+ Data Ingestion
+ Data Pipeline
+ Azure Services: Blob Storage, Data Factory, SQL DB
+ Databricks and Power BI
+ Data Warehousing; Analytics Reporting
+ Extract, Transform and Load (ETL) process
+ Some Power BI Data Visualization technical skills (Documentation, Data Gathering, Power Query, Data Modelling, Report Design, Data Analysis Expression (DAX), Page Navigation and Button, Business and Analytics Reporting, Performance Optimization, Deployment and Power BI Service, Scalability)
+ Feedback and Continuous Improvement
  
## Data Engineering Process
1. Ingestion of Data into the SQL Database: This was accomplished with Import File method in SQL Server with inheritance of all data schema 
2. Creation of Linked Services in ADF: A Linked service was created in ADF to directly extract the table from the SQL Server; After which it was copied into another link service with the help of another Liked service. The Data is now restored in a container in Azure blob storage. 
3. Data Warehousing in Databricks: This same data is ingested into Databricks so as to create the appropriate analytical report as KPI demands. The Azure blob storage was mounted in databricks, data extracted and  a Temptable was created with only the relevant fields, this will propell faster runnig of the Report and reduce cosumed capacity thereby saving cost. This Temp table was used to created another table to be used for the Visualization in power BI. [Get the Pyhton codes here](https://github.com/Abdur-RasheedAde/Complete_Azure_DE_Pizza_Project/blob/main/Azure_Data_Engineering_Project.ipynb) A copy of the exported data from the temTable is also here [Exported_Table](https://github.com/Abdur-RasheedAde/Complete_Azure_DE_Pizza_Project/blob/main/Final_Exported_Pizzadata.csv)
4. Data Visualization with PowerBI: The Analytical reported created was linked to Power BI Desktop the development environment for the Visualization Report. This Visualization is an extnesive one as it has 6 major KPIs that are measured in the Report.

## KPI Building 
While creating building the visualization, the following KPIs were considered;
1. Total Pizza Sold
2. Total Orders, total revenue, Average pizza per order
3. Monthly Pizza Sales
4. Daily, hourly trend of sales
5. Sales by pizza category and pizza size
6. Top 5 Order pizza

## Report Design and Visualization
The Report Canvas was designed in Power Point and imported to PowerBI as canvas background. Here is a sample of the slide in Power Point   
<img src="https://github.com/Abdur-RasheedAde/Complete_Azure_DE_Pizza_Project/blob/main/Slide1.PNG" width=75% height=75%>  
6 pages were created; Includig each for the Piza_Category (Supreme, Veggie, Classic and Chicken), a consolidated page and an home page. \
_Home_ page is the landing page while _Consolidated_ has the general report without filter while other pages has filtered reports accroding to their page name.
On each page, the new card visual is used to hold Total Sales, Quantity and Average_Unit_Price, Line Chart is used for the series analysis while a column and bar chart are adopted for the Pizza_size and Top 5 Pizza Ordered analysis. The last image is the button for page navigation. 

A sample of the consolidated page is below:
<img src="https://github.com/Abdur-RasheedAde/Complete_Azure_DE_Pizza_Project/blob/main/Homevisual.PNG" width=75% height=75%>  
Link to the dashboard is here 👉 [Click to view PowerBI Report](https://app.powerbi.com/view?r=eyJrIjoiMzgwMjA2YWItNzhmMi00NDU5LTlkMTYtOTA1Y2Y1ODliZTFhIiwidCI6IjMyNzk2YmUyLTYwZmItNGRhMi04ZDI2LTA2ZTU5MzhlNmU2YiIsImMiOjh9)

## Conclusions 
1. Azure Data Synapse is a comprehensive Azure service that unifies all Azure data services in one space including databricks from ingestion (ADF) to data warehousing and visualizatio (PowerBI)
2. Databricks is one of the leading cloud big data Softaware as a service (SaaS) for big Data supporting both Python and SQL.
3. It is awesome for Data warehousing and ETL process and simple visualization dashboard.

Thanks for taking time to go through this report! and I am open to collaborate with you on any Data Engineering projects exploring Azure data services or other cloud big data platforms especially Databricks, Snowflake, AWS and GCP, you can always reach me on adeoyerasheed30@gmail.com Ciao 🤝
