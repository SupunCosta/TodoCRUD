# Todo App

This project is a Todo application built with ASP.NET Core and Entity Framework Core.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- [.NET 8.0 SDK]([https://dotnet.microsoft.com/download/dotnet/8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0))
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

### Installation

1. **Clone the repository:**

    ```sh
     git clone [https://github.com/yourusername/todo-app.git](https://github.com/npkarunarathne/Todos/edit/master/README.md)
    cd todo-app
    ```

2. **Restore dependencies:**

    ```sh
    dotnet restore
    ```

3. **Set up the database:**

    Update the database:**

    ```sh
    dotnet ef database update -c TodosDbContext
    ```

### Configuration

Ensure your `appsettings.json` or `appsettings.Development.json` is configured correctly to connect to your SQL Server instance. Below is an example configuration:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=your_server_name;Database=TodoDb;User Id=your_username;Password=your_password;"
  },
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft": "Warning",
    }
  },
  "AllowedHosts": "*"
}
#   T o d o C R U D  
 