# My .NET 8 Web Application

This is a sample web application built using .NET 8. It demonstrates the use of ASP.NET Core MVC to create a simple web application with a home page.

## Project Structure

The project consists of the following main components:

- **Controllers**: Contains the controllers that handle HTTP requests.
  - `HomeController.cs`: Manages requests for the home page.

- **Models**: Contains the data models used in the application.
  - `SampleModel.cs`: Defines the data structure for the application.

- **Views**: Contains the Razor views for rendering HTML.
  - `Home/Index.cshtml`: The main view for the home page.
  - `Shared/_Layout.cshtml`: A shared layout for the application.

- **wwwroot**: Contains static files such as CSS.
  - `css/site.css`: The main stylesheet for the application.

- **Configuration Files**:
  - `appsettings.json`: Configuration settings for the application.
  - `Program.cs`: The entry point of the application.
  - `Startup.cs`: Configures services and the request pipeline.

- **Project File**:
  - `my-dotnet8-webapp.csproj`: The project file that defines dependencies and build settings.

## Getting Started

To run this application locally, follow these steps:

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/my-dotnet8-webapp.git
   cd my-dotnet8-webapp
   ```

2. **Restore dependencies**:
   ```
   dotnet restore
   ```

3. **Run the application**:
   ```
   dotnet run
   ```

4. **Access the application**:
   Open your web browser and navigate to `http://localhost:5000`.

## Deployment

To deploy this application to Azure Web App, follow these steps:

1. Create a new Azure Web App in the Azure portal.
2. Configure the deployment settings to connect to your GitHub repository.
3. Set up the build configuration to use .NET 8.
4. Deploy the application.

## License

This project is licensed under the MIT License. See the LICENSE file for details.