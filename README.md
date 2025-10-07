Uber Data Analytics Dashboard 📊🚗
This project presents a comprehensive analysis of Uber ride data from New York City. The primary goal is to uncover patterns and insights from the dataset through a complete data analytics workflow, including data cleaning, transformation, and visualization.

The process begins with sourcing raw data from Kaggle, pre-processing it with Python, and culminates in a dynamic, interactive dashboard built in Power BI to present the findings.

📈 Project Workflow
The project followed a systematic approach from data extraction to visualization:

Data Sourcing: The raw dataset was downloaded from Kaggle. It contained information about Uber pickups in NYC, including date/time stamps and geographical coordinates.

Data Cleaning & Feature Engineering (Python): A Python script was developed to perform the initial, heavy-duty cleaning. Key tasks included:
Handling missing or null values.
Converting the Date/Time column to the correct datetime format.
Validating data integrity and removing duplicates.
The cleaned data was then exported to a new .csv file, making it ready for analysis.

Data Modeling & Visualization (Power BI):

Import & Transformation: The cleaned .csv file was imported into Power BI. Power Query Editor was used for final transformations like setting correct data types, renaming columns for clarity, and creating conditional columns.
DAX Measures: DAX was used extensively to create powerful, reusable calculations that go beyond basic aggregations. Examples include:
Total Rides = COUNTROWS(UberData)
Weekend Rides = CALCULATE([Total Rides], UberData[DayOfWeek] IN {"Saturday", "Sunday"})

Time intelligence functions to analyze trends.
Dashboard Design: An interactive dashboard was designed with a combination of visuals (charts, KPIs, maps, slicers) to present the insights in an intuitive and business-friendly manner.

🖼️ Dashboard Preview
![Main Dashboard Screenshot](https://via.placeholder.com/800x450.png?text=PASTE+YOUR+MAIN+DASHBOARD+URL+HERE)
![Hourly Trends Screenshot](https://via.placeholder.com/800x450.png?text=PASTE+YOUR+HOURLY+ANALYSIS+URL+HERE)
![Map Screenshot](https://via.placeholder.com/800x450.png?text=PASTE+YOUR+GEOSPATIAL+MAP+URL+HERE)
