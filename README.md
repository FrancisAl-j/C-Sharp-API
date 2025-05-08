## ASP.NET CORE Web API

write this commands on the terminal in (vs code)

- dotnet new webapi -o api
- dotnet watch run <- to run the program

The "program.cs" is a very important cs file
(It is like the back of our TV)

## Connecting PostgreSQL to ASP.NET Core

# Creating a table on PostgreSQL

- psql -U postgres <- if This doesn't work then just create a database in the pgadmin ui

# Run this command in Terminal in you project folder "api"

- dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL
- dotnet add package Microsoft.EntityFrameworkCore.Design
- dotnet add package Microsoft.EntityFrameworkCore.Tools

## LINQ

# Language Intergrated Query

Write LINQ queries in C# for SQL server databases,
XML documents, ADO.NET datasets,
and any collection of objects that support
IEnumerable or the generic IEnumerable<T> interfaces
