# Week 4

## Learning data tools

### Spreadsheets

* Column --> Vertical
* Row --> Horizontal
* Attribute - A characteristic  or quality of data used to label a column in a table. 
* Observation - All of the attributes for something contained in a row of a data table.

### SQL

* Can be used to 
    -   Store
    -   Organize
    -   Analyze
* Supersized datasheet
* Useful for large datasets
* Databases that use SQL - Oracle, MySQL, PostgreSQL, Microsoft SQL, Server, etc.
* Basic structure of an SQL query
    -   SELECT [*Choose the column(s) you want*] - Use SELECT to choose the columns you want to return.
    -   FROM [*From the appropriate table*] - Use FROM to choose the tables from the database, where the columns you want are located.
    -   WHERE [*a certain condition is met*] - Use WHERE to filter for certain information.

    ![example](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/-kywAm5gQTOMsAJuYEEzSA_2dab01a4a07d4ad386cb1f56d7e3b8b6_Screen-Shot-2020-11-11-at-4.27.02-PM.png?expiry=1665532800000&hmac=MAWBCESSyy_Umt6W85tgHmHcXGiYAAKuWy2WYy5Y0K8)

* When you query databases, you use SQL to communicate your question or request.
* The semicolon is a statement terminator and is part of the American National Standards Institute (ANSI) SQL-92 standard.
* if you are looking for all customers with a last name that begins with the letters “Ch," the WHERE clause would be:- ```WHERE field1 LIKE 'Ch%'```
* LIKE clause is very powerful because it allows you to tell the database to look for a certain pattern! The *or % sign  is used as a wildcard to match one or more characters. 
* Comments are text placed between certain characters, /* and */, or after two dashes (--).
![example](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/YFUj-vGxT4aVI_rxsY-GGg_0a4b434ac7c14176a192d0f65be62142_Screen-Shot-2020-11-11-at-4.32.20-PM.png?expiry=1665532800000&hmac=cew0bmsIidRjcT1HaE2j4l14Q6Mr25JiIRdm9evuJ0g)
* Assign a new alias using ```AS```
* Not equal to is written as ```<>```

### Data Visualization

* Data visualization is the graphical representation of information.
* Data analysts use data visualizations to explain complex data quickly, reinforce data analysis, and create interesting graphs and charts.
* Create visualizations that make your data easy to understand and interesting to look at.
* There are many different tools you can use for data visualization. 
    -   You can use the visualizations tools in your spreadsheet to create simple visualizations such as line and bar charts.
    -   You can use more advanced tools such as Tableau that allow you to integrate data into dashboard-style visualizations. 
    -   If you’re working with the programming language R you can use the visualization tools in RStudio.