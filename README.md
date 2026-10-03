# TaskFlow

TaskFlow is a backend project management and task management system built with **ASP.NET Core** and **SQL Server**. It provides a secure API for managing projects and tasks, with authentication, authorization, token-based security, and real-time communication.

## 🚀 Overview

TaskFlow was built to practice and demonstrate backend development concepts using the .NET ecosystem, including API design, authentication and authorization, database integration, token management, and real-time communication.

## ✨ Key Features

* Project and task management
* User authentication and authorization
* JWT-based access tokens
* Refresh token support
* Secure API endpoints
* RESTful API design
* Real-time communication using SignalR
* SQL Server database integration

## 🛠️ Tech Stack

### Backend

* **ASP.NET Core**
* **C#**
* **RESTful APIs**
* **JWT Authentication**
* **Authentication & Authorization**
* **SignalR**

### Database

* **SQL Server**

### Tools

* **Git**
* **GitHub**

## 🏗️ Architecture

The project follows backend development practices focused on:

* Separation of responsibilities
* Secure authentication and authorization
* RESTful API design
* Maintainable and structured backend code
* Database-driven application design

## 🔐 Authentication & Authorization

TaskFlow uses **JWT-based authentication** to secure API endpoints.

The authentication flow includes:

* Access tokens for authenticated API requests
* Refresh tokens for obtaining new access tokens
* Authorization to restrict access to protected resources

## 📡 Real-Time Communication

TaskFlow integrates **SignalR** to support real-time communication between the server and connected clients.

This allows relevant application updates to be delivered without requiring clients to continuously poll the API.

## 🗄️ Database

TaskFlow uses **SQL Server** for persistent application data.

The backend communicates with the database through the .NET data access layer.

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

* [.NET SDK](https://dotnet.microsoft.com/download)
* SQL Server
* Git

### Clone the Repository

```bash
git clone https://github.com/haya08/Task-flow.git
cd Task-flow
```

### Configure the Application

Update the application's configuration with your SQL Server connection string and authentication settings.

For example:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "YOUR_CONNECTION_STRING"
  }
}
```

> **Important:** Never commit passwords, API keys, JWT secrets, or other sensitive credentials to the repository.

### Run the Project

Restore the project dependencies:

```bash
dotnet restore
```

Build the project:

```bash
dotnet build
```

Run the application:

```bash
dotnet run
```

The API will then be available through the configured application URL.

## 📌 Project Status

This project was developed as a backend project to practice and demonstrate practical **ASP.NET Core backend development** concepts.

## 👩‍💻 Author

**Haya Ahmed Hussien**

* GitHub: https://github.com/haya08
* LinkedIn: https://linkedin.com/in/hayaahmedhussien
