# Blazor-ListView-Entity-Framework

A quick getting started project to create an Entity Framework application with Blazor ListView component. The Blazor ListView Component is a list-like interface that **Repository Description**  
This repository contains a **quick‑start Blazor application** that demonstrates how to integrate the Syncfusion **Blazor ListView** component with **Entity Framework**.

The Blazor ListView is a list‑like UI component that allows users to select single or multiple items and display data in an interactive, hierarchical structure across different layouts and views. This project shows how database‑driven data can be retrieved using Entity Framework and presented using the Blazor ListView component.

## Project Overview
The purpose of this project is to help developers understand how to build a **data‑driven Blazor application** using Entity Framework in combination with the Syncfusion Blazor ListView component. It serves as a reference for binding database content to ListView controls and displaying it in an interactive UI.

## Features
- Integration of **Syncfusion Blazor ListView**
- Data access using **Entity Framework**
- Database‑driven list rendering
- Support for single and multiple item selection
- Hierarchical data presentation in ListView
- Blazor‑based application structure

## Prerequisites
Ensure the following requirements are met before running this project:
- **Visual Studio 2019** (version 16.6 or later)
- **.NET Core SDK 3.1.3**
- SQL Server LocalDB (for the sample database)
- Syncfusion Blazor packages
- Valid Syncfusion license key (if required)

> **Note:** .NET Core SDK 3.1.3 requires Visual Studio 2019 version 16.6 or newer.

## Installation

### Clone the Repository
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/SyncfusionExamples/Blazor-ListView-Entity-Framework.git
```
### Configure Database Connection
Update the database connection string in the following file:
```bash
Shared/DataAccess/DataContext.cs
```
Example connection string:
```C#
optionsBuilder.UseSqlServer(
  @"Data Source=(LocalDB)\MSSQLLocalDB;
    AttachDbFilename='D:\Blazor-ListView-Entity-Framework\Shared\App_Data\NORTHWND.MDF';
    Integrated Security=True;
    Connect Timeout=30");
```
Ensure the database file path matches your local environment.
### Running the Application
Run the project using Visual Studio 2019.
Once the application starts, open the browser to view the Blazor ListView populated with data retrieved through Entity Framework.
An example output can be seen below:
`./Client/wwwroot/images/EFListView.gif`

## Configuration
The ListView and Entity Framework configuration is handled through:
- Entity Framework DbContext configuration
- Blazor component binding logic
- ListView property and selection configuration
You can further customize:
- Data models
- ListView templates and layouts
- Selection and interaction behavior

## Documentation
- General Syncfusion documentation:
https://help.syncfusion.com/
- Blazor Introduction:
https://blazor.syncfusion.com/documentation/introduction
- Blazor ListView – Getting Started:
https://blazor.syncfusion.com/documentation/listview/getting-started

## Additional Resources
- Syncfusion Blazor ListView product overview:
https://www.syncfusion.com/blazor-components/blazor-listview
- Syncfusion Blazor community forums:
https://www.syncfusion.com/forums/blazor-components

## Troubleshooting
- Ensure the database file path is correct in the connection string.
- Verify that SQL Server LocalDB is installed.
- Restore NuGet packages if build errors occur.
- Rebuild the solution if UI changes are not reflected.

## Support

Product support is available for through following mediums.

* Creating incident in Syncfusion [Direct-trac](https://www.syncfusion.com/support/directtrac/incidents?utm_source=npm&utm_campaign=filemanager) support system or [Community forum](https://www.syncfusion.com/forums/essential-js2?utm_source=npm&utm_campaign=filemanager).
* New [GitHub issue](https://github.com/syncfusion/ej2-javascript-ui-controls/issues/new).
* Ask your query in [Stack Overflow](https://stackoverflow.com/?utm_source=npm&utm_campaign=filemanager) with tag `syncfusion` and `ej2`.

## License

Check the license detail [here](https://github.com/syncfusion/ej2-javascript-ui-controls/blob/master/license).