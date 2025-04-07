# Complete Developer Network (CDN) - Freelancer User Management API

This is a RESTful API for managing freelancers in the **Complete Developer Network (CDN)** system. The API allows you to register, update, delete, and retrieve user information. The application also supports recycling deleted IDs to avoid gaps in the ID sequence.

## Project Overview

The API offers the following features:
- **Register a new user** (POST)
- **Retrieve all users** (GET)
- **Retrieve all usernames** (GET)
- **Update user information** (PUT)
- **Delete a user** (DELETE)

## Technology Stack

- **ASP.NET Core Web API**
- **Entity Framework Core** (EF Core)
- **SQL Server** (or any RDBMS of your choice)

## Features

- **RESTful API**: All the necessary CRUD operations for managing users.
- **Error Handling**: Includes error handling for missing users during update and delete operations.

## Setup Instructions

### Prerequisites

- [.NET 6.0](https://dotnet.microsoft.com/download) or later installed on your machine.
- A **SQL Server** instance or any RDBMS to store user data.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ivan77800/WebApplication.git   
   cd cdn-user-management-api
