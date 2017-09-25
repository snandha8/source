# SQL Toolkit for Azure

This is a set of build and deployment tasks to support Azure Databases.

- It uses TFS Service Endpoints to connect to Azure.
- Displays output from PRINT and RAISEERROR commands

- Please note that firewall rules are no longer created on the fly by these tasks. 
- Ensure Allow access to Azure services is switched on for your SQL Server in the firewall.
   
## Tasks

- RunStoredProcedure - This task will run a Stored Procedure against your database.

- RunSqlScripts - This task will run all of the SQL scripts in the specifed folder against your database in the numeric file name order. ex order:  1_script.sql, 2_script.sql, 12_script, 21_Script.

- RunSqlCommand - This task will run an adhoc query aganst your database.

- RunSingleSqlScript - This task will run a specified SQL script against your database.

## Website: 

[SQL Toolkit for Azure](https://github.com/snandha8/source)