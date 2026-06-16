# Blazor Server DataGrid - Async CRUD with Default Toolbar Items

This sample combines a Blazor Server front end, [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid), and a simple Web API backend.
It demonstrates asynchronous data loading and default toolbar-based CRUD operations in one project.

## Overview

This project shows a Blazor Server app with DataGrid that:

- loads order data asynchronously from a Web API endpoint
- uses the default toolbar for add, edit, delete, update, and cancel actions
- performs create, update, and delete requests through a controller-backed API

## Features

- Asynchronous data binding from a Web API service
- Built-in DataGrid toolbar for CRUD operations
- Server-side controller endpoints for add, edit, and delete actions
- Paging support for order records
- Simple in-memory data source for quick testing

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/EJ2-DataGrid-BlazorServer-GridEdit-Asynchronousupdate-Default-Toolbaritems.git
cd EJ2-DataGrid-BlazorServer-GridEdit-Asynchronousupdate-Default-Toolbaritems
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/getting-started-with-server-app

**Demo**: https://blazor.syncfusion.com/demos/datagrid/overview?theme=fluent2