# Blazor DataGrid — Disable Editing for Particular Rows

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
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-disable-editing-for-particular-row.git
cd blazor-datagrid-disable-editing-for-particular-row
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

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/in-line-editing

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=fluent2