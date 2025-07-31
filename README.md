# ExpenseManager.API

A Simple Web Based Expense Manager API using .NET C# and AWS DynamoDB

## Clean Architechture

| Project                           | Use Cases                                              |
| --------------------------------- | ------------------------------------------------------ |
| `ExpenseManager.Domain`           | Entities, Interfaces, Domain Events, Value Objects     |
| `ExpenseManager.Application`      | DTOs, Interfaces, Validations, Commands & Queries      |
| `ExpenseManager.Infrastructure`   | EF Core, External API Services, Persistence            |
| `ExpenseManager.API`              | Core API, Controllers, DI, Middlewares                 |
| `ExpenseManager.Shared`           | Common Abstractions, Result, BaseEntity, Logging, etc. |
| `ExpenseManager.UnitTests`        | Unit Tests for Domain and Application                  |
| `ExpenseManager.IntegrationTests` | Unit Tests for API and Infrastructure                  |
