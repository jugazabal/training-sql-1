﻿# Training: SQL 💻
Welcome to this repository of training materials for querying in SQL.

The training materials will be written in **T-SQL** (Transact-SQL). 📜

## Who are these training materials for? 👔
These training materials are designed with the enterprise/business user in mind.

In particular, it is created from this perspective to enable users to better choose the material they need according to what they will use SQL for.

## How are the training materials organised? 🗃

They are organised according to level of usage:
- **Light-user 🥉:** For those performing basic querying operations to retrieve lightly-wrangled data from SQL. They will have **READ-ONLY** or higher access to the database. Topics covered are:
    + Basic relational database theory
    + Basic query to retrieve all records/data from a table
    + Choosing unique records in a column
    + Filtering data from a table
    + Sorting/Arranging/Ordering data from a table
    + Grouping your data to aggregate it
    + Joining data from different tables next to each other
    + Attaching data from similarly structured tables on top of each other
    + Creating new columns in your data
    + Changing columns to a different data type
    + Using conditional if-else statements

- **Medium-user 🥈:** For those performing more advanced querying operations to retrieve heavily wrangled data from SQL. They will have **READ-ONLY** or higher access to the database. Topics covered are:
    + Differences between Tables and Views
    + Three types of temporary tables for storing data
    + Subquerying the data  
    + Ranking groups of variables by a counter
    + Pivoting data from long to wide shape
    + Unpivoting data from wide to long shape
    + Data matrix/tidy data principles

- **Heavy-user 🥇:** For those perforrming data management roles to store objects permanently in SQL. They will have **READ-WRITE** or higher access to the database. Topics covered are:
    + Dynmaic SQL querying
    + What makes a well-governed database?
    + Creating and updating tables
    + Importing data into SQL
    + Indexing columns to improve querying speeds
    + Adding constraints to columns to restrict entries that can go inside it
    + Using stored procedures and functions to do more bespoke operations
    + Database triggers for tracking activity
    + Version-controlling databases 

## Is there anything I need alongside the files? 👀🧠
The materials exist as interactive notebook-style files so that the user can seamlessly read and interact with SQL queries. For those familiar with Jupyter Notebooks in Python, this is exactly that.

Alongside the files in this repo, you will need to: 

1. Download and install [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download?view=sql-server-ver15) 
1. Download and import the [AdventureWorks database](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15) into SQL

It is recommended that you do most of your SQL-related work in Microsoft's **SQL Server Management Studio (SSMS)**, or any other SQL engine (though the relevance of these mateirlas are lower).

This is because SSMS offers a better graphical user interface (GUI) to enable you to easily explore databses, tables, Views, stored procedures etc. whereas the programme we are using in these materials, Azure Data Studio, does not have the same functionality.

## How do I open the notebook files? 📖
To open and use the notebooks:
    
1. Open the software, **Azure Data Studio**
1. Save the `ipynb` file onto your desktop
1. Click on `File` -> `Open File` -> navigate to file titled `training_sql_lightuser.ipynb`


## Who can I contact if I think this material is pants? 👖
Please post it as an [Issue](https://github.com/avisionh/Training-SQL/issues) on the repository. I will then look at it.