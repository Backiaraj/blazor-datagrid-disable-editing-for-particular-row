# Blazor DataGrid - Disable Editing for Particular Rows

A sample Blazor application demonstrating how to conditionally disable editing for specific rows in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component based on row data criteria.

## Overview

This repository demonstrates how to selectively disable row editing in the Blazor DataGrid component. The sample prevents editing for rows where the **Ship Country** is "RUSSIA" by leveraging the `OnActionBegin` event to cancel edit operations based on custom validation logic.

## Features

- **Conditional Row Editing** - Disable editing based on specific data values or business rules
- **Event-driven Validation** - Leverage `OnActionBegin` to intercept and cancel edit operations
- **Inline Editing** - Edit row data directly within the grid interface
- **Paging Support** - Handle large datasets efficiently with pagination
- **Toolbar Actions** - Edit, Cancel, and Update operations for complete row management

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`DisableEditing.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-disable-editing-for-particular-row
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/in-line-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=fluent2