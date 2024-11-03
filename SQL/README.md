# Project Title: LITA_DB LIMITED

## Table of Contents
[Project Overview](#project-overview)

[Project Objectives](#project-objectives)

[Data Sources](#data-sources)

[Tool Used](#tool-used)

[Data Analysis Process](#data-analysis-process)


### Project Overview
---
This project involves analyzing a company's employee data to provide insights into various aspects such as staff identification, salary distribution, sales performance and so on. The project aims to leverage SQL to perform data analysis including data cleaning, querying and reporting to help streamline business processes and support data driven decision making.

### Project Objectives
To;
- improve data management.
- generate business insights.
- facilitate decision making.
### Data Sources
---
The data utilized in this project was generated by the faclitator for instructional purposes and reflects hypothetical staff details. The data was designed to simulate real world scheduling scenerios, allowing for practical application of SQL queries.

### Tool Used 
---
- SQL [Structured Query Language]
  1. For Data import 
  2. For Cleaning
  3. For Analysis
  
###  Data Analysis Process
---

- Data Import:
  This include bringing in data into SQL from different sources
  
- Data Cleaning and Preparation:
This includes handling duplicates, blank cells and text manipulation and extration using **`SQL COMMANDS`** such as;
1. DDL: **`CREATE`**, **`ALTER`**, **`DELETE`**, **`TRUNCATE`**.
2. DML: **`INSERT`**, **`UPDATE`**, **`DROP`**.
3. DQL: **`SELECT`** to fetch data.
4. TCL: **`ROLLBACK`**, **`COMMIT`**.
5. DCL: **`GRANT`**, **`REVOKE`**

- Data Analysis Techniques: This involve using analytical functions annd **`SQL CLAUSES`** such as **`WHERE`**, **`TOP`**, **`GROUPBY`**, **`ORDERBY`**, **`HAVING`** to derive insights from data. Functions include;
  **`SUM()`**, **`AVG()`**, **`MAX()`**,  **`MIN()`**, **`COUNT()`**.

```SQL
SELECT SUM(PROFIT)  as [TOTAL PROFIT HERO] FROM [dbo].[International Breweries]
WHERE COUNTRIES = 'NIGERIA' AND YEARS =2017 and brands= 'hero'
GROUP BY BRANDS
ORDER BY 1 DESC
```

![IMG_3271](https://github.com/user-attachments/assets/9627a31f-75d0-4c48-a73b-d648771b1f75)

![IMG_3270](https://github.com/user-attachments/assets/49d971b8-a14b-4c7c-bf2d-08a071124117)