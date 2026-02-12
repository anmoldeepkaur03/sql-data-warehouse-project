/*
-----------------------------------------------------------------------------
Create Database and Schemas
-----------------------------------------------------------------------------
Script Purpose:
This script create new database names 'DataWarehouse' after checling if it already exists.
If the databae exists, it is dropped and recreates. Additionally, the script sets up three schemas within the database: 
'bronze', 'silver', 'gold'.

WARNING:
 Running this script will drop the entire 'DataWarehouse' database if it exists
 All the data in the database will be permanently deleted. Proceed with caution and ensure you have proper backups.
*/

USE master;
GO

-- Drop and recreate the 'DataWarehouse' database
IF EXISTS (SELECT 1 FROM sys.databases WHERE name = 'DataWarehouse')
BEGIN
   ALTER DATABASE DataWarehouse SET SINGLE_USER WITH ROLLBACK IMMEDIATE;
   DROP DATABASE DataWarehouse;
   END;
   GO

-- Create the 'DataWarehouse' database
CREATE DATABASE DataWarehouse;
GO

USE DataWarehouse;
GO


-- Create Schemas
create schema bronze;
go
create schema silver;
go
create schema gold;
go
