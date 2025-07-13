# Week4WebApihandsOn

# WebAPI Hands-On Project (.NET Core)

This is a comprehensive .NET Core Web API project designed to demonstrate practical implementation of modern web development practices. It covers essential topics such as RESTful services, Swagger API documentation, testing with Postman, JWT-based authentication, CORS configuration, custom filters for authorization and exception handling, and integration with Apache Kafka for real-time streaming use cases.

---

## Key Features

- RESTful API with complete CRUD (Create, Read, Update, Delete) operations  
- Interactive API documentation using Swagger (Swashbuckle)  
- HTTP request testing and simulation using Postman  
- Secure endpoints using JWT (JSON Web Token) authentication and role-based authorization  
- Implementation of custom authorization and exception filters  
- CORS (Cross-Origin Resource Sharing) configuration for client-side integration  
- Kafka integration for real-time message streaming (chat application example)  

---

## Prerequisites

Before you begin, ensure you have the following installed:

- [.NET SDK (latest stable version)](https://dotnet.microsoft.com/download)  
- [Visual Studio 2022+ or Visual Studio Code](https://code.visualstudio.com/)  
- [Postman API testing tool](https://www.postman.com/)  
- [Apache Kafka and Zookeeper (for Kafka Integration)](https://kafka.apache.org/quickstart)  

---

## Running the Application

To build and run the application locally:

```bash
dotnet restore        # Restores NuGet packages
dotnet build          # Builds the application
dotnet run            # Runs the API on localhost

Common API Endpoints
HTTP Verb	Endpoint	Description
GET	/api/employee	Retrieves all employees
GET	/api/employee/{id}	Retrieves employee by ID
POST	/api/employee	Creates a new employee
PUT	/api/employee/{id}	Updates an existing employee
DELETE	/api/employee/{id}	Deletes an employee by ID
GET	/api/auth/token	Generates a JWT token