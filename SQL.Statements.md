Keep copy all the interesting query:

SQL SERVER – FIX: Database Diagram Error 15517 – Cannot Execute as the Database Principal Because the Principal ‘dbo’ Does Not Exist

USE AdventureWorks2017
GO
SELECT SUSER_SNAME(sid), * from sys.database_principals

USE [AdventureWorks2017]
GO
ALTER AUTHORIZATION ON DATABASE::[AdventureWorks2017] TO [sa]
GO
