# CleanArchitecture

A C# Clean Architecture Template.  I created this in Visual Studio 2022.

Uses Mediator pattern (MediatorR library) and also fluent Validator (a validation library for .NET that uses a fluent interface and lambda expressions for building strongly-typed validation rules).

Solution split up into 5 projects (4 are class libraries):

Domain
Application
Infrastructure
Presentation
WebApi (ASP.NET Core Web API Project) -> has dependencies to Application, Infrastructure and Presentation projects.






