## How to Run This Project

### Prerequisites
- .NET 8 SDK
- SQL Server (or SQL Server Express)

### Setup Instructions
1. Clone the repository.
2. Open `RaceDay2.sln` in Visual Studio.
3. Update the `DefaultConnection` string in `appsettings.json` to match your SQL Server instance.
4. Open the Package Manager Console and run `Update-Database`.
5. Press `F5` to run the application.

### Default Admin Login
- **Email**: kamophathup2@gmail.com
- **Password**: @Kamokgelo072

### Running Tests
- Open the **Test Explorer** in Visual Studio (Test -> Test Explorer).
- Click **Run All Tests**. (There are 10+ integration tests utilizing an in-memory database).
