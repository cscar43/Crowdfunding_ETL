# Crowdfunding_ETL

This repository contains the Project 2 submission for the task of extracting and transforming data from an Excel file. 

The goal is to create 4 separate DataFrames: one for categories, another for subcategories, cleaning up the contacts, and modifying the crowdfunding table provided

We then had create a Crowdfunding Database, write a schema to import our csv files into, and verify the table data by doing a select statement for each table.

**Files**
The repository includes the following files:

* ETL_Mini_Project_Starter_Code.ipynb: the code that updates, modifies, and exports the cleaned up csv files
* crowdfunding_db_schema.sql: the schema that i used to create the tables for the dataframes, and the code to check to make sure the table fetched the data.

A Resource Folder with the following:
* category.csv: The exported Categories DataFrame.
* subcategory.csv: The exported Subcategories DataFrame.
* campaign.csv: The exported modified Campaign DataFrame.
* contacts.csv: the exported cleaned up and modified Contacts DataFrame.
