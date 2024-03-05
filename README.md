# Crowdfunding ETL Mini Project

Welcome to the Crowdfunding ETL Mini Project repository! This project uses Python and Pandas to build an Extract, Transform, Load (ETL) pipeline. The goal is to extract data from Excel files, transform it into meaningful DataFrames, create CSV files, design a database schema, and finally, load the data into a PostgreSQL database.

## Project Structure

- **ETL_Mini_Project_Masih.ipynb**: This Jupyter notebook contains Python code and is organized into sections corresponding to the project instructions.

- **Resources**: This folder contains the input Excel files.

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

- The order of import requires campaign to be imported last as it has FOREIGN KEYS linked to all other 3 tables

- Verify the correctness of the data by running SELECT statements.

## Contributors

- Ali Yazdan

- Brett Osborne

- Rachel Jiang

- Masih Qadir 

![image](https://github.com/MasihQadir007/Crowdfunding_ETL2/assets/149569402/a0e6a9ef-c4ee-4386-a469-20f2830b6283)
