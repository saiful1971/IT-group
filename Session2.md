We joined meeting through Google Meet.
Test the latest features with SQL Server 2017 Developer Edition. Full-featured free edition.
https://cloudblogs.microsoft.com/sqlserver/2019/01/21/test-the-latest-features-with-sql-server-2017-developer-edition/
Free Download SQL Server Management Studio (SSMS) 
Then download sample database from Microsoft.com
AdventureWorks installation and configuration. OLTP downloads. AdventureWorks2017.bak
Create a directory under C:\drive C:\ITGroup>Copy file AdventureWorks2017.bak
Connect SQL Server Management Studio
Right Click Database and restore AdventureWorks2017.bak
Expand Database. Choose AdventureWorks2017.bak expanded (+). 
Expand Table, choose Person.Address. Right click and choose Select Top 1000 Rows
/****** Script for SelectTopNRows command from SSMS  ******/
SELECT TOP (1000) [AddressID]
      ,[AddressLine1]
      ,[AddressLine2]
      ,[City]
      ,[StateProvinceID]
      ,[PostalCode]
      ,[SpatialLocation]
      ,[rowguid]
      ,[ModifiedDate]
  FROM [AdventureWorks2017].[Person].[Address]
  
  Practice SQL tutorial
  to be continued...........
  
  Setup Microsoft Teams (To communicate each other and post all the links for Study):

https://teams.microsoft.com/l/team/19%3a6880eda705fb4fbc89cb67677f67d7b8%40thread.tacv2/conversations?groupId=8c55a49f-d59c-4e08-806e-93138f13d38a&tenantId=349e58a3-df8c-4fa4-915f-3e8715021412
Babu Bhai gave some Study Material Like Configure a classic board and Create an issue and a sub-task with Jira:

https://support.atlassian.com/jira-software-cloud/docs/configure-a-classic-board/

https://support.atlassian.com/jira-software-cloud/docs/create-an-issue-and-a-sub-task/

We create BabuITGroup (Jira Software::

https://babuitgroup.atlassian.net/jira/software/projects/BAB/boards/1

We create few TO DO task, then IN PROGRESS, READY FOR REVIEW AND DONE.

How to assign different TASK to different people.

Babu Bhai talk about AWS Cloud Certification:

https://www.aws.training/
  
