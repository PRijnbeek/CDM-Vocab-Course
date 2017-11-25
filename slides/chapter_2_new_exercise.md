---
title: Connecting to the server
key: f983958a7580558ae552bf6b8f3af012


--- type:TitleSlide key:55ade73467
## Installing DataGrip

*** =lower_third
name: Peter Rijnbeek
title: installing DataGrip

*** =script





--- type:FullSlide key:2c84384b7d
## Follow the steps below to connect to the datasource


*** =part1
1. Open data sources under the File menu
2. Click on + sign and add an Azure (Microsoft Database)
3. Set the connection details 

    Host: emif.database.windows.net
    
    Database: SYNPUF1000
    
    User: course@emif

    Password: <Provided during the Course>

    URL: is filled in automatically
4. If needed download the driver and then test the connection
 


*** =script


--- type:FullSlide key:b02798a3bc
## Showing the database structure in DataGrip

*** =part1
Go to View-> Tool windows -> database. 

This will show your new database on the left of your screen. If you now expand the database you see "schemas". Double click on "schemas" and add the dbo (default) schema and click outside that window to close it (or press enter)

You are now ready to perform queries in a console window. If you do not see the SQL consol on the right you can open it by selecting your database and clicking on the small 'QL' symbol on the top of that window. 

*** =script

--- type:FullSlide key:49c43b9261
## Introduction

*** =part1

During the course we will be studying the OHDSI Standardized Vocabularies by running queries against the SYNPUF CDM we loaded on a SQL Server instance in the Microsoft Azure cloud. To connect to this CDM we will use DataGrip which is a fantastic database querying tool (https://www.jetbrains.com/datagrip/) I would highly recommend. You can install DataGrip as a free 30 days evaluation. We will not explain how to install DataGrip here.

Before you start you have to connect to the training CDM as is described in the next few slides. 


*** =script


--- type:FinalSlide key:d7f9ed77eb
## Let's practice!

*** =script

Now let's try some examples.

