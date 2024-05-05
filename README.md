# Telecom-ETL-Using-SSIS

## Introduction
This project aims to implement an ETL (Extract, Transform, Load) process for a telecommunications company. As an ETL Developer/Consultant, the task involves storing data from periodic CSV files into a database while performing necessary transformations and validations on the data.
## Project Overview
The telecommunications company generates CSV files every 5 minutes containing essential data regarding various customer transactions within a specific timeframe. The provided table outlines the data stored in the CSV file along with the required processing steps before storing it in the database.
## Processing Requirements
1. Apply mapping rules to transform and validate data before storing it in the database.
2. Reject records that do not meet specified conditions and store them in a separate table along with the original CSV file name.
3. Register additional data during the database storage process to ensure data quality.

## Additional Data to Register
1. Number of transactions in the CSV file.
2. Number of transactions stored in the database.
3. Number of rejected transactions due to failure to meet conditions.
4. Link the stored data in the database with the original CSV file.



## Project Dataset Schema Overview

![image](https://github.com/Mahmoud-khaled-m/Telecom-ETL-Using-SSIS/assets/85359683/d19eb1c6-5e1d-43eb-bf3b-e5cbbd204ed6)

![image](https://github.com/Mahmoud-khaled-m/Telecom-ETL-Using-SSIS/assets/85359683/a333a9d2-ddfc-45b3-8013-27bda5e579b4)

## ETL Processes:
  1. Extract Data from CSV files.
  2. Process and transfer data.
  3. Dealing with data that do not meet the quality requirements like Nulls and missing values.
  4. Error Handling
  5. Archive files that have been processed and transferred.
  6. Auditing the processed data.
## Control Flow Graph
![image](https://github.com/Mahmoud-khaled-m/Telecom-ETL-Using-SSIS/assets/85359683/d41d2d66-2857-4b12-8920-544eaca002a6)

## Data flow 

![image](https://github.com/Mahmoud-khaled-m/Telecom-ETL-Using-SSIS/assets/85359683/b1b8bfeb-412d-4036-9b72-dd902a6e961c)

## Result using SSMS

![image](https://github.com/Mahmoud-khaled-m/Telecom-ETL-Using-SSIS/assets/85359683/52f3af59-76e7-405e-b79a-2468570ba83d)




