# unlocking-ep28

# CommandGuildline

## create api project
dotnet new  
dotnet new webapi -n workshopep28.api

## create unitTest project
dotnet new xunit -n workshopep28.test

## add reference from api to unitTest project
dotnet add workshopep28.test/workshopep28.test.csproj reference workshopep28.api/workshopep28.api.csproj  

## add package reference to unitTest project  
dotnet add package FluentAssertions  
dotnet add package Moq  

## create ionic web project
ionic start 


## publish  api project to deploy to azure
dotnet publish
