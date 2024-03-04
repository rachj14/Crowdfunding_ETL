# Crowdfunding ETL Mini Project

Welcome to the Crowdfunding ETL Mini Project repository! This project focuses on building an Extract, Transform, Load (ETL) pipeline using Python and Pandas. The goal is to extract data from Excel files, transform it into meaningful DataFrames, create CSV files, design a database schema, and finally, load the data into a PostgreSQL database.

## Project Structure

- **ETL_Mini_Project_BOsborne.ipynb**: This Jupyter notebook contains the Python code for the ETL pipeline. It is organized into sections corresponding to the project instructions.

- **Resources**: This folder contains the input Excel files, `crowdfunding.xlsx` and `contacts.xlsx`.

- **category.csv**: CSV file containing the transformed data for the Category DataFrame.

- **subcategory.csv**: CSV file containing the transformed data for the Subcategory DataFrame.

- **campaign.csv**: CSV file containing the transformed data for the Campaign DataFrame.

- **contacts.csv**: CSV file containing the transformed data for the Contacts DataFrame.

- **crowdfunding_db_schema.sql**: PostgreSQL schema file specifying table structures, data types, primary keys, and foreign keys.

## Instructions

### 1. Category and Subcategory DataFrames

- Execute code in the notebook to create the Category and Subcategory DataFrames.

- Export the DataFrames to CSV files (`category.csv` and `subcategory.csv`) and save them in the repository.

### 2. Campaign DataFrame

- Execute code in the notebook to create the Campaign DataFrame.

- Export the DataFrame to a CSV file (`campaign.csv`) and save it in the repository.

### 3. Contacts DataFrame

#### Option 1 (Python Dictionary Methods)

- Execute code in the notebook to import and transform the Contacts data using Python dictionary methods.

- Export the DataFrame to a CSV file (`contacts.csv`) and save it in the repository.


### 4. Crowdfunding Database

- Inspect the four CSV files.

- Sketch an Entity-Relationship Diagram (ERD) using QuickDBD and save it in the repository.

- Create a PostgreSQL schema file (`crowdfunding_db_schema.sql`) based on the ERD.

- Create a new PostgreSQL database named `crowdfunding_db`.

- Execute SQL queries to create tables and verify the table creation.

- Import CSV files into the corresponding SQL tables.

- Verify the correctness of the data by running SELECT statements.


![image](https://github.com/rachj14/Crowdfunding_ETL/assets/149569402/fb7aba58-3c63-4da8-93c9-afb273484932)
