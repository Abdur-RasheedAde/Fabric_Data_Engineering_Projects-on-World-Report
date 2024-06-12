# World Report Fabric_Data_Engineering_Projects

![Slide1](https://github.com/Abdur-RasheedAde/Fabric_Data_Engineering_Projects/blob/main/DEArchitecture.png)

##  Project Overview
This is a complete End-to-End Fabric Data Engineering project where PDF, Excel Power Query, Python Beautiful Soup, SQL, Pyspark, lake House and Power BI are explored. The project ingest data from multiple sources like the web, pdf and csv into the Fabric Lake house, created a robust Data pipeline in Fabric for the ETL process and stored the data in a LakeHouse Table from where Power BI Visualization Report was built. 

## Data Source:
1.  Web:Data were scrapped from www.worldometers, catking.in and www.geeksforgeeks
2.  PDF: A pdf file was downloaded from this website [Click to download pdf](https://www.miles-and-more.com/content/dam/mmg/pdf/191029_BLOOM_Laendertabelle_EN_FINAL.pdf)
3.  Json: Data was also extracted from this json file 👉 [Download_json_file](https://github.com/Abdur-RasheedAde/Fabric_Data_Engineering_Projects/blob/main/continent-populations.json)

## DE Technical Skills:
+ Data Ingestion
+ Data Pipeline
+ Fabric Data Storage: Lake House, Beautiful Soup library, Excel Power Query 
+ Data Warehousing; Analytics Reporting
+ Extract, Transform and Load (ETL) process
+ Some Power BI Data Visualization technical skills (Documentation, Data Gathering, Power Query, Data Modelling, Report Design, Data Analysis Expression (DAX), Page Navigation and Button, Business and Analytics Reporting, Performance Optimization, Deployment and Power BI Service, Scalability)
+ Feedback and Continuous Improvement
  
## Data Engineering Process
1. Data Ingestion: Data was ingested from multiple sources like web, pdf and json with the help of beautiful soup library, Excel Power Query and Pyspark respectively. the pdf file was loaded to Excel with the use of Power Query which extracted the data effortlessly and it was saved as a csv file for Lakehouse storage.  
2. Creation of Lake House: A Lakehouse known as World_Data_Project Lakehouse was created in OneLake to encapsulate all the Data Engineering items.
3. ETL Process: The whole Extract Transform and Load Processes were done in 2 Jupyter Notebooks in the Lakehouse with the use of Beautiful Soup library, pyspark and Pandas library. The Transformation includes and not limited to:
-  Change data type and Column names of some columns
-  remove the "$" and "," in some columns
-  joining of multiple tables
-  Correcting the names of some Countires like Algerie, USA, UAE...\
The well transforemd final data was loaded to a LakeTable for Analytics Purposes.
-  [View first_Pyhton codes here](https://github.com/Abdur-RasheedAde/Fabric_Data_Engineering_Projects/blob/main/World_Data.ipynb)
-  [View second_pyhton codes here](https://github.com/Abdur-RasheedAde/Fabric_Data_Engineering_Projects/blob/main/World_Continent.ipynb)

4. Data Visualization with PowerBI: A Power BI Report was built directly from the loaded LakeHouse Tables with KPIs ranging from Population metrics, to LandArea and Fertility Rate. The Power Bi is also hosted within the workspace and all data modeling and report building were done in the cloud. 

## KPI Building 
While creating building the visualization, the following KPIs were considered;
1. Top and Bottom Countries by Population
2. Top and Bottom Countries by LandArea
3. Top and Bottom Countries by Fertility Rate
4. Countries, Capital, Currency, President and Prime Minister

## Report Design and Visualization
+ The Report Canvas was designed in Power Point and imported to PowerBI as canvas background. Here is a sample of the slide in Power Point.
+ 5 pages were created; Includig each for the KPIs above and a home page.
+ The _Home_ page is the landing page with page navigation to other pages.
+ On each page, a map visual and bar chart were explored along with a Matrix table.
+ A sample of the home page is below:
Link to the dashboard is here 👉 [Click to view PowerBI Report](https://app.fabric.microsoft.com/groups/29456d2a-e1f3-4e67-91a9-41bc1e4fe5d1/reports/820d6455-aae0-4125-82d5-85f5e26b1430/cb1051de495b69a10c08?experience=power-bi)

## Conclusions 
1. Microsoft Fabric is one-stop shop that replicate all Azure Data Services (known as items in Fabric) in one space. These items include DataFactory, Power BI, LakeHouse, Notebooks, Pipeline and so on. 
2. It can iterract with all internal and external data sources like Azure, AWS, GCP, Dataverse and coud services like Databricks, Snowflake and others.
3. It extensively supports SQL, Python, Scala and java Programming Languages
4. It is awesome for Data warehousing and ETL process and visualization.

Thanks for taking time to go through this report! and I am open to collaborate with you on any Data Engineering projects exploring Fabric, Azure data services or other cloud big data platforms especially Databricks, Snowflake, AWS and GCP, you can always reach me on adeoyerasheed30@gmail.com Ciao 🤝
