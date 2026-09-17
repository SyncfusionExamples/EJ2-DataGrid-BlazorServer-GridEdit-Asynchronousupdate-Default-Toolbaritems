# Syncfusion Blazor Server DataGrid - Asynchronous Web API CRUD Editing with Default Toolbar Items

## Overview

This sample demonstrates how to bind a Syncfusion Blazor DataGrid to data that is loaded asynchronously from a Web API service in a Blazor Server application. The sample also shows how users can perform create, update, and delete operations through the Grid's built-in toolbar commands without implementing custom action buttons. It provides a reference implementation for developers who need asynchronous data access combined with standard Grid editing workflows in a server-side Blazor application.

## Key Features

- Uses the Syncfusion Blazor DataGrid within a Blazor Server application.
- Demonstrates asynchronous data retrieval from a Web API endpoint.
- Supports create, update, and delete operations through default Grid toolbar items.
- Shows integration between Blazor Server UI components and backend Web API services.
- Includes dedicated `Controllers` and `Data` folders used to support asynchronous CRUD processing.
- Uses repository structure that separates UI, backend endpoints, and data models for maintainability.

## Prerequisites

* Visual Studio 2022 or Visual Studio Code
* .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file: `DefaultToolbarItemSample.sln`
3. Restore NuGet packages.
4. Set the startup project to:`DefaultToolbarItemSample` 
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the directory containing `DefaultToolbarItemSample.csproj`.
4. Restore NuGet packages:

```bash
dotnet restore
```

5. Run the application:

```bash
dotnet run
```

## Project Structure

`Pages/` — contains the Blazor page implementation that renders the Syncfusion DataGrid sample.

`Controllers/` — contains Web API endpoints responsible for asynchronous data retrieval and CRUD processing.

`Data/` — contains sample data models and supporting data-access logic used by the application.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official Syncfusion DataGrid editing documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/editing

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.