# Lab 1: Setup Environment
- Open the integrated terminal.
- Change directories (cd) to the folder that will contain the project folder.
- Run the following commands:
  
      .NET Core CLI
      dotnet new webapi -o TodoApi
      cd TodoAp i
      dotnet add package Microsoft.EntityFrameworkCore.SqlServer
      dotnet add package Microsoft.EntityFrameworkCore.InMemory
      code -r ../TodoApi

- When a dialog box asks if you want to add required assets to the project, select Yes.
- The preceding commands:
  - Creates a new web API project and opens it in Visual Studio Code.
  - Adds the NuGet packages which are required in the next section.

## Output: 
http://localhost:5087/WeatherForecast
