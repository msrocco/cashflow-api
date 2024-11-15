## About the Project

This **API**, built with **.NET 8**, uses **Domain-Driven Design (DDD)** principles to create a well-organized solution for personal expense management. It allows users to log their expenses, capturing details like title, date and time, description, amount, and payment type. All data is securely stored in a **MySQL** database.

The **API** follows a **REST** architecture, using standard **HTTP** methods to keep communication simple and efficient. It’s also equipped with **Swagger** documentation, providing an easy-to-use, interactive interface for developers to explore and test the API endpoints.

The API is supported by some essential NuGet packages:
- **AutoMapper** for mapping domain objects to request and response objects, helping us avoid repetitive code and simplifying development.
- **FluentAssertions** for unit testing, which makes it easier to write clear and readable test statements.
- **FluentValidation** for implementing validation rules directly in request classes, keeping the code organized and straightforward.
- **EntityFramework**, an ORM (Object-Relational Mapper), which lets us interact with the database using .NET objects, so we don’t need to write SQL queries manually.

### Features

- **Domain-Driven Design (DDD)**: Modular structure that simplifies understanding and maintenance of the application's domain.
- **Unit Testing**: Comprehensive tests using FluentAssertions to ensure functionality and quality.
- **Report Generation**: Ability to export detailed reports to **PDF and Excel**, providing effective visual analysis of expenses.
- **RESTful API with Swagger Documentation**: Documented interface that facilitates integration and testing for developers.

### Built With

![badge-dot-net]
![badge-windows]
![badge-visual-studio]
![badge-mysql]
![badge-swagger]

## Getting Started

To get a local copy up and running, follow these simple steps.

### Requirements

* Visual Studio 2022+ or Visual Studio Code
* Windows 10+ or Linux/MacOS with [.NET SDK](dot-net-sdk) installed
* MySQL Server

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/msrocco/cashflow-api.git
    ```

2. Fill in the necessary information in the `appsettings.Development.json` file.
3. Run the API and enjoy testing it! :)

<!-- Links -->
[dot-net-sdk]: https://dotnet.microsoft.com/en-us/download/dotnet/8.0

<!-- Badges -->
[badge-dot-net]: https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff&style=for-the-badge
[badge-windows]: https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=fff&style=for-the-badge
[badge-visual-studio]: https://img.shields.io/badge/Visual%20Studio-5C2D91?logo=visualstudio&logoColor=fff&style=for-the-badge
[badge-mysql]: https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff&style=for-the-badge
[badge-swagger]: https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=000&style=for-the-badge
