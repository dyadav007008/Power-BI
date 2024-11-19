# Power-BI:

# Course Outline
## Introduction to Power BI Desktop
## Connecting and shaping data
## Creating a Data Model
## Calculating Measures with DAX
## Visualizing Data with Dashboards
## Optimizing Power Bi performace

Course Project:

- THE SITUATION: You’ve just been hired as a Business Intelligence Analyst by AdventureWorks*, a global
manufacturing company that produces cycling equipment and accessories
- THE BRIEF: The management team needs a way to track KPIs (sales, revenue, profit, returns), compare
regional performance, analyze product-level trends, and identify high-value customers.
All you’ve been given is a folder of raw csv files, which contain information about
transactions, returns, products, customers, and sales territories.
- THE OBJECTIVE: Use Power BI Desktop to:
• Connect and transform the raw data
• Build a relational data model
• Create calculated columns and measures with DAX
• Design an interactive dashboard to visualize the data

Power BI:
Microsoft Power BI is a self-service business intelligence platform, which includes both desktop and web-based applications for connecting, modeling, and visualizing data.

WHY POWER BI?

- Connect, transform and load millions of rows of data
• Access data from virtually anywhere (database tables, flat files, web, cloud services, folders, etc.), and create fully automated workflows to extract, transform and load data for analysis
- Build relational models to blend data from multiple sources
• Create table relationships to analyze holistic performance across an entire relational data model
- Define complex calculations using Data Analysis Expressions (DAX)
• Enhance datasets and enable advanced analytics with powerful and portable DAX expressions
- Bring data to life with interactive reports and dashboards
• Build professional-quality reports and dashboards with best-in-class visualization tools
- Develop a versatile, in-demand skill set
• Power BI is the industry leader in self-service BI, and the skills you build in this course will be highly transferrable

## EXCEL VS. POWER BI
![image](https://github.com/user-attachments/assets/bcdc9a61-ef8a-468f-abf6-2be5c428e06b)


# Power BI Workflow

1. Power Query Editor: Data is loaded & transformed in the Power Query Editor
2. Model View: Data models are configured in the Model View
3. Data View: Table features & calculations are added in the Data View
4. Report View: Visuals & reports are designed in the Report View

# CONNECTING & SHAPING DATA

# Topics:
- 1. Intro to Power Query
- 2. Data Connectors
- 3. The Query Editor
- 4. Connection Modes
- 5. Data QA & Profiling
- 6. Table Transformations
- 7. Calendar Tools
- 8. Combining Queries

## FRONT-END VS. BACK-END: Power BI Desktop essentially has two distinct environments: a front-end and a back-end
• The front-end includes the Data, Model & Report views, where most of the modeling, analysis and visualization takes place
• The back-end includes the Power Query Editor, where raw data is extracted, transformed, and loaded to the front-end (ETL)

## BACK-END:

• Connect & extract data using pre-built connectors
• Profile & QA the data to explore, clean and prepare it for modeling and analysis
• Transform & shape tables to add new features, modify values, group records, or sort and filter columns
• Merge or append queries to join and combine them prior to loading to the front-end
• Perform advanced transformations using custom M code (out of scope for this course)

## Front End:
• Build data models by creating table relationships between primary and foreign keys
• Add calculated measures & columns using Data Analysis Expressions (DAX)
• Design reports to visualize the data and create interactive, dynamic dashboards
• Publish & share your Power BI workbooks using Power BI Service (cloud application)

## TYPES OF DATA CONNECTORS:

Power BI can connect to virtually any type of source data, including (but not limited to):
• Flat files & Folders (csv, text, xlsx, etc.)
• Databases (SQL, Access, Oracle, IBM, etc.)
• Power Platform (Datasets, Datamarts, Dataflows, Dataverse, etc.)
• Azure (Azure SQL, Analysis Services, Databricks, etc.)
• Online Services (SharePoint, GitHub, Dynamics 365, Google Analytics, Salesforce, Power BI Service, etc.)
• Other (Web feeds, R scripts, Spark, Hadoop, etc.)

POWER QUERY EDITOR: 

![image](https://github.com/user-attachments/assets/1e45db03-6d82-4c1c-a882-e88bfa399fe6)

![image](https://github.com/user-attachments/assets/cfe9f11c-8b94-450e-a184-f382c05758f8)

![image](https://github.com/user-attachments/assets/b4ed49dd-ea91-42e3-969d-6ef4ffaec142)


ASSIGNMENT: TABLE TRANSFORMATIONS

1. Create queries to connect to the two new .csv files
2. Name your queries Product Category Lookup and Product Subcategory Lookup
3. Confirm that column headers have been promoted and that all data types are correct
4. Add a new column to extract all characters before the dash ("-") in the Product SKU column, and name it ”SKU Type”
5. Update the SKU Type calculation above to return all characters before second dash, instead of the first
6. Replace zeros (0) in the Product Style column with “NA”
7. Close and load to your data model

## STORAGE & CONNECTION MODES
Power BI Desktop supports several types of storage and connection modes:
• Import: Tables are stored in-memory within Power BI and queries are fulfilled by cached data (default)
• DirectQuery: Tables are connected directly to the source and queries are executed on-demand at the data source
• Composite Model (Dual): Tables come from a mix of Import and DirectQuery modes, or integrate multiple DirectQuery tables
• Live Connection: Connect to pre-published Power BI datasets in Power BI Service or Azure Analysis Services

## DATA PROFILING: COLUMN QUALITY
Profiling tools like column quality, column distribution, and column profile allow you to explore the quality, composition, and distribution of your data before loading it into the Power BI front-end
![image](https://github.com/user-attachments/assets/09f51a3b-86b7-4b49-ab63-e598ea572f2e)

![image](https://github.com/user-attachments/assets/058a9ee1-576c-4043-9f73-d08d32d5ea82)

![image](https://github.com/user-attachments/assets/9b29a9c0-b65b-4cd0-b433-47588a38df71)

## Text Column

![image](https://github.com/user-attachments/assets/07141fa8-59c5-4675-814c-d5e1f788a6b1)

## Numerical Tools

![image](https://github.com/user-attachments/assets/ef6fe7cc-9027-4705-82ce-e1bca98f066b)

Kry Objective:

1. What is our average product cost? 714.437
2. How many colors do we sell our products in? 9
3. How many distinct customers do we have? 18148
4. What is the maximum annual customer income? 170000
5. Return the tables to their original state
