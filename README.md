## EJ2-DataGrid-Core-dotnet3-DataBinding-url-adaptor

### Repository Description

This repository demonstrates how to bind the Syncfusion EJ2 DataGrid to a remote data source using the UrlAdaptor in an ASP.NET Core 3.x application.

## Project Overview

This sample application explains how to display data in the Syncfusion EJ2 Grid by fetching records from a server-side URL using the UrlAdaptor. The grid operates in a read-only mode and focuses only on retrieving and displaying data from the server.

The sample is useful for scenarios where data needs to be loaded from an API or controller action without implementing insert, update, or delete operations.

In ASP.NET Core 3.x, Json.NET is not included by default. Therefore, additional JSON configuration is required to correctly serialize and deserialize the data returned to the grid.


## Features
- Data binding using EJ2 Grid UrlAdaptor
- Server-side data retrieval
- Paging enabled for large datasets
- Read-only grid configuration
- Compatible with ASP.NET Core 3.x

## Prerequisites
- .NET Core SDK 3.x
- Visual Studio 2019 or later
- Syncfusion EJ2 ASP.NET Core components
- Basic knowledge of ASP.NET Core MVC

## Usage

The grid is configured to retrieve data from a server endpoint using the UrlAdaptor. 

## Reference Documentation
 
- [Getting started with ASP.NET CORE Grid](https://ej2.syncfusion.com/aspnetcore/documentation/grid/getting-started-core) 
- [Remote Data Binding](https://ej2.syncfusion.com/aspnetcore/documentation/grid/data-binding/remote-data)
- [API Reference](https://help.syncfusion.com/cr/aspnetcore-js2/syncfusion.ej2.grids.grid.html)
