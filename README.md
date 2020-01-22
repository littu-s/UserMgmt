# UserMgmt
Simple ASP.Net MVC project for demonstrate CRUD operation in a table.

Tools used:
Visual Studio 2017
.Net Framework 4.6.1
ASP.Net MVC
C# 
SQL Server

Table:
CREATE TABLE [dbo].[User] (
    [Id]         INT          IDENTITY (1, 1) NOT NULL,
    [FirstName]  VARCHAR (50) NOT NULL,
    [LastName]   VARCHAR (30) NOT NULL,
    [Email]      VARCHAR (50) NOT NULL,
    [Mobile]     VARCHAR (15) NOT NULL,
    [BirthDate]  DATETIME     NOT NULL,
    [ModifyDate] DATETIME     NOT NULL,
    PRIMARY KEY CLUSTERED ([Id] ASC)
);

ModifyDate is set as default to the created/edited date of the user. So, it will not be displayed in "Create/Edit" Forms
