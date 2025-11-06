# Data Cleaning Utility & Date Table Generator Function --Python-Library

## 📌 Project Overview

This project contains two complete Python self built libraries using **Object Orientated Programming System** particulaly **_Abstration & Inheritance_** designed to automate repetitive data preparation tasks:

✅ Data Cleaning Function Library

✅ Date Calculation / Date Table Function Library

I built these tools to solve real business problems where datasets arrive messy, inconsistent, etc or missing crucial time-based features.
Instead of manually cleaning data every time, this module lets me import one library and perform every transformation interactively on any dataset. It is user friendly and each tasks is narrowed down to user intext, it also allows for customized new column name in every task.

**This library has been successfully used across:**
- Customer datasets
- Sales datasets
- Retail data
- CSV and Excel datasets
- SQL extracted data
- Extracting date 

It removes human error, standardizes cleaning steps, and saves hours of work on every project.
By automating repetitive transformations, the library guarantees consistent outputs, improves data quality, and allows analysts to focus on insights instead of consistently fixing messy files.


## Key Features Of Data Cleaning Funtion -- Automative Python Library

**✔ Automatic handling of missing values:**

    - Droping table rows with missing values
    - Droping rows base on a column with missing values
    - Filling integer column missing values with calculation on its table or other table
    - Filling string column missing values with another column
    - Filling column missing values with a character/ digit
    
**✔ Removing and Replacing Inconsistency:**

    - Cleaning Inconsistencies using Regular Expression
    - Removing Duplicates base on table row duplicate or column
    - Removing and Replacing data with another character or value base on a condition

**✔ Convert data types:**

    - Converting to string data type
    - Converting to integer data type
    - Converting to flote data type
    - Converting to datetime data type
    
**✔ Substring:**

    - Splitting Column(s) Base On A Delimiter base on mutiple or single delimiter
    - Spliting Column(s) Base on Slicing

**✔ Removing  Unwanted rows and columns:**

    - Deleting Columns
    - Deleting Rows base on index location or condition
    
**✔ Rearranging and Renaming columns:**

    - Rearrange Columns base on index or column name
    - Rename Columns
    
**✔ Text proper Data:**

    - Capitalize The Every First Word Of Text
    - Capitalize ALL Text
    - Capitalize Only The First Word Text
    - LowerCase ALL Text
    
**✔ Concatinating columns:**

    - Concat Columns
    - Concat Columns With A Fix Value
    - Concat Columns With A With Part Of another Column Data using regular expression

**✔ Converting Unit:**

  All unit converstion of **(Speed, Temperature, Volumne, pressure, Power, Energy, Mass & Weight, Length & Distance, Area)** which,
  
    - Convert All Data In a Column
    - Convert Part Of The Data In a Column

## Key Features Of Date Table Generator Funtion --  Python Library

**✔ Year Extraction:**

- This Extract Year From a date time column

**✔ Quarter Extraction:**

- This Extract,
   - Quarter
   - Start of Current, Next & Previous Quarter
   - End of  Current, Next & Previous Quarter

**✔ Month Extraction:**

- This Extract,
   - Month Number
   - Month Year both abbreviated eg.(Jan-2023) and full eg. (January-2023)
   - Month Name both abbreviated eg.(Jan-Dec) & Full eg. (January - December)
   - Start of Current, Next & Previous Month
   - End of  Current, Next & Previous Month

**✔ Week Extraction:**

- This Extract,
   - Week Year Number eg. (1-52)
   - Week Day Number eg. (0-6)
   - Week Day abbreviated eg.(Mon-Sun) and full eg. (Monday- Sunday)

**✔ Day Extraction:**

- This Extract,
   - Day Month Number eg. (1-30 or 31)days
   - Day Year Number eg.(1-365 or 366)days

**✔ Month Extraction:**

- This Extract,
   - Month Number
   - Month Year both abbreviated eg.(Jan-2023) and full eg. (January-2023)
   - Month Name both abbreviated eg.(Jan-Dec) & Full eg. (January - December)
   - Start of Current, Next & Previous Quarter
   - End of  Current, Next & Previous Quarter

**✔ Date Difference Calculation:**

- This Calculate Date Difference in **Month, Day, Year** in
   - Two date column
   - Date column and todays date

**✔ Date Addition Calculation:**

- This Calculate Date Difference in **Month, Day, Year, Week, Business Days** in

## Installation & Importing as a Library
I Created a folder then a .py file called clean_modules for Data cleaning funtion and  Date_Table for the date table funtion

Data Cleaning Library                          |                     Date Table Generator Library                
:---------------------------------------------:|:-----------------------------------------------:
![](Visualization_of_Global_superstore_1.png) |  ![](Visualization_of_Global_superstore_2.png)

This can be imported and used in any project like this
**Data Cleaning
```python
from Clean_Data.clean_module import Data_Cleaning
cleaning = Data_Cleaning(Name of table or data frame)
cleaning.Cleaning_options()
```

Date Table Extraction
```python
from Create_Date_Table.Date_Table import Calculate_Date
create = Calculate_Date(df)
```

## Example Usage (Real-World Scenario)
Data cleaning in a product sales project using the self built Data Cleaning Library
![](Visualization_of_Global_superstore_1.png)

Exracting a new month year column in a product sales project using the self built Date Table Library
![](Visualization_of_Global_superstore_1.png)

## Sample Data Before and After Date Cleaning
The Date set Consist of **duplicate, irregular date format, imporper text, nullvalues, mixed unit and several inconsistencies**

                                    Messy Data Set             
:---------------------------------------------:|:-----------------------------------------------:
![](Visualization_of_Global_superstore_1.png) |  ![](Visualization_of_Global_superstore_2.png)

                                    Cleaned Data Set             
:---------------------------------------------:|:-----------------------------------------------:
![](Visualization_of_Global_superstore_1.png) |  ![](Visualization_of_Global_superstore_2.png)

## Sample Date Extracted Tables
The Data displayed shows all extracted date using the date table extractor function

Messy Data Set             
:---------------------------------------------:|:-----------------------------------------------:
![](Visualization_of_Global_superstore_1.png) |  ![](Visualization_of_Global_superstore_2.png)


## Why This Library Matters (Impact by Function)

### ✅ Data Cleaning Functions — Impact & Business Value

**☑️ Transforms messy, inconsistent raw data into analysis-ready datasets automatically**

Instead of spending hours fixing spelling errors, missing values, wrong formats, duplicates, or blank records, the function standardizes everything in seconds, turning unusable files into clean, reliable data.

**Fixes human errors that usually break dashboards and machine learning models**

Detects and corrects problems like:
- wrong date and data formats
- wrong data types (e.g., numbers stored as text)
- Inconsistencies
- Mixed conversion units
-incomplete records
These silent errors are a major cause of wrong insights during data analysis and machine learning models.

**☑️ Gives a 100% consistent cleaning process for every new dataset**

Companies often clean data manually, which leads to mistakes and different formats across files.
This function enforces the same cleaning rules every time,  no variation, no missing steps, no skipped checks.

**☑️ Saves 70–90% of data preparation time**

A dataset that might take 2–5 hours to clean manually can be processed in less than 10 seconds.
For departments that clean data daily, that means hundreds of hours saved per month.

**☑️ Protects business decisions from wrong insights**

Dirty data leads to wrong metrics, wrong forecasting, and wrong reports.
This function ensures:
✅ customer counts are correct
✅ revenue calculations are not inflated
✅ duplicates don’t double-count transactions
✅ text fields like names, products, and locations are normalized

**☑️ Handles messy real-world data from Excel, Google Sheets, Web exports, SQL, CSV, CRM systems, and Surveys**

The function isn’t limited to one format. It works across multiple data sources and different schema structures which is a major requirement in real business environments.

**☑️ Prevents dashboard failures in Power BI, Tableau, or Python notebooks**

Cleaning fixes the common issues that cause broken visualizations:
- null values
- wrong aggregation
- missing categories
- mismatched join keys

**☑️ Reusable forever - just import and clean**

Once imported as a package or module, any dataset from any project can be cleaned with just:

```python
from Clean_Data.clean_module import Data_Cleaning
cleaning = Data_Cleaning(df)
cleaning.Cleaning_options()
```

**☑️ Makes collaboration and teamwork easier**

Any analyst on the team can use the same cleaning rules without rewriting code can guarantee clean and uniform data across multiple projects.


### ✅ Date Table Generator Functions — Impact & Business Value

**☑️ Builds an enterprise-grade Date Dimension Table automatically**
Generates every time-intelligence field (Year, Month, Quarter, Week, Day, Fiscal Period, Weekend/Weekday, Month Name, etc.) used in professional analytics and data warehousing. These metrics also allows finance and retail teams to compare performance accurately across time periods and stamps.

**☑️ Prevents broken dashboards and inaccurate time-series analysis**
Many datasets skip dates due to weekends, public holidays, or missing entries. The function fills all gaps and creates a continuous calendar which eliminating misleading dips or spikes in revenue, sales, or customer activity charts.

**☑️ Transforms raw timestamps into business-ready features**
Converts a single date column into 20+ actionable time columns used for forecasting, churn analysis, cohort performance, sales trends, and seasonality detection.

**☑️ Saves analysts from manually engineering date tables every project**
What normally takes 45–90 minutes to build from scratch in SQL or Excel is now done in seconds, with zero manual formatting or typing errors.

**☑️ Boosts forecasting accuracy and trend visibility**
With clean chronological ordering, the function allows machine learning models and BI dashboards to detect true seasonality and customer behavior patterns that are normally hidden.

**☑️ Reusable for any industry**
Works for retail sales, hospital records, e-commerce, logistics, HR attendance, survey analytics, banking transactions — once built, it becomes a universal time backbone for all datasets.


## Conclusion

This project is more than a script, it is a reusable, production-ready Python library built to solve real data problems faced in business environments.
Instead of cleaning the same issues over and over, the library automates the process, enforces consistency, and eliminates human error.
It transforms raw, messy files into clean, trusted data that can be used confidently for reporting, analysis, machine learning, and business decisions. This library shows the ability to engineer scalable data workflows the same way enterprise data teams do.

It also demonstrates skills in:
⇛ Python programming
⇛ OOP (Object-Oriented Design)
⇛ Data modeling and feature engineering
⇛ Automation and reproducibility
⇛ Building tools that reduce workload and increase accuracy

Any analyst, data engineer, or business team member can install the library and clean datasets in seconds instead of hours.
That means faster dashboards, more accurate insights, and better decisions with zero manual corrections.

This project reflects my goal as a Data Analyst:
✔ Make data reliable
✔ Make data usable
✔ Make data ready for business impact
