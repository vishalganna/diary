# Diary Project - Income, Expenses, and Investments Tracker

## Overview
This project is designed to help users maintain a detailed record of their financial activities, including income, expenses, and investments. It uses **Azure Function App** for backend processing and **Blazor WebAssembly (WASM)** for the frontend, built using **C#**. The application allows users to track their finances, generate reports, and make data-driven decisions.

## Technologies Used
- **Azure Functions App** (Serverless backend)
- **Blazor WebAssembly** (Frontend)
- **C#** (Programming Language)
- **Azure Storage** (for data storage)
- **Entity Framework Core** (Database management)
- **Bootstrap** (UI framework)

## Features
- Record daily income and expenses
- Track investments and their growth
- Generate financial reports (monthly, yearly)
- User authentication (via Azure AD)
- Responsive UI (supports desktop and mobile)

## Prerequisites
- Visual Studio 2022 or higher
- Azure Subscription
- .NET 8 SDK or later
- SQL Database on Azure (for data storage)
- Azure Functions Tools for Visual Studio

## Setup Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/vishalganna/diary.git
cd diary-project
```

### 2. Set up Azure Function App:
- Create a new Function App on the Azure Portal.
- Configure the function settings and deploy the backend code.

### 3. Set up Database:
- Set up Azure SQL Database or any other supported database.
- Configure connection strings in the `appsettings.json`.

### 4. Build and Run the Project:
- Open the solution in Visual Studio.
- Build the project and run the app.

### 5. Frontend Configuration:
- Modify API URLs in the Blazor client app (`App.razor` or `HttpClient`).
- Ensure authentication is set up (using Azure AD or another provider).

## Usage
- **Track Income:** Add income entries with details such as amount, date, and category.
- **Record Expenses:** Add expense entries with categories and payment methods.
- **Investment Portfolio:** Track investment growth and view historical performance.

## Future Enhancements
- Support for recurring transactions
- Email notifications for expense limits
- Integration with third-party financial APIs

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---