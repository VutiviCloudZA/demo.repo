# .NET 9 ASP.NET Core Web Application

This repository contains a .NET 9 ASP.NET Core web application with a standard MVC architecture.

## Project Structure

The project follows the standard ASP.NET Core MVC structure:

- **Controllers**: Contains the MVC controllers that handle HTTP requests
- **Models**: Contains the data models used by the application
- **Views**: Contains the Razor views that render the UI
- **wwwroot**: Contains static files like CSS, JavaScript, and images

## Getting Started

### Prerequisites

- .NET 9 SDK
- Visual Studio 2022 or Visual Studio Code

### Running the Application

1. Clone this repository
2. Navigate to the project directory
3. Run the application using the .NET CLI:

```bash
cd WebApp
dotnet run
```

4. Open your browser and navigate to `https://localhost:5001` or `http://localhost:5000`

## Development Environment

The application is configured with different settings for development and production environments:

- **Development**: Detailed error information, developer exception page
- **Production**: Error handling, HSTS enabled

## Features

- MVC architecture
- Responsive design using Bootstrap
- Standard routing configuration
- Static file serving

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
