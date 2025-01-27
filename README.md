# Online Market

An ASP.NET Core MVC project that serves as a foundational structure for creating an online marketplace. This project includes basic functionality for rendering views, managing routing, and setting up the project pipeline.

## Features

- **ASP.NET Core MVC Framework**: Leverages the Model-View-Controller architecture for clean code separation.
- **Views**:
  - `Home/Index`: Main landing page.
  - `Home/Privacy`: Privacy policy page.
  - Shared layouts like `_Layout.cshtml` for consistent UI across the app.
- **Error Handling**: Implements error view (`Error.cshtml`) for exception handling.
- **Static Assets**: Includes Bootstrap, jQuery, and custom CSS/JS for building responsive and interactive user interfaces.
- **Development and Production Configuration**: Supports environment-specific settings through `launchSettings.json`.
- **Routing**: Default routing configured for `Home` controller.

## Project Structure

Controllers: Contains the controllers that handle HTTP requests and responses.
Models: Contains the data models used in the application.
Views: Contains the views for the MVC pattern.
Properties: Contains project properties and configuration files.
wwwroot: Contains static files such as CSS, JavaScript, and images.
Program.cs: The entry point of the application.
Startup.cs: Configures services and the app's request pipeline.
appsettings.json: Configuration settings for the application.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/online-market.git
2. Open the project in Visual Studio.
3. Restore dependencies:
   dotnet restore
4. Build and run the project:
   dotnet run
5. Access the app in your browser at https://localhost:5001 or http://localhost:5000.

## Prerequisites
.NET Core SDK 3.1 or later
Visual Studio 2019 or later with ASP.NET and web development workload installed.

## Key Configurations
Development environment: Set in launchSettings.json under the ASPNETCORE_ENVIRONMENT key.
Routing: Configured in Startup.cs to use the Home controller and Index action by default.

##Technologies Used
ASP.NET Core MVC
Bootstrap (CSS framework)
jQuery (JavaScript library)
