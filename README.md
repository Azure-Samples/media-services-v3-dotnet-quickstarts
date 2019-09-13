---
page_type: sample
languages:
- csharp
products:
- azure
description: "The project in this repository was created using Visual Studio 2017. It targets netcoreapp2.0. The code in the project uses 'async main',"
urlFragment: media-services-v3-dotnet-quickstarts
---

# Azure Media Services v3 quickstart starter samples

The project in this repository was created using Visual Studio 2017. It targets netcoreapp2.0. The code in the project uses 'async main', which is available starting with C# 7.1. See [this blog](https://blogs.msdn.microsoft.com/benwilli/2017/12/08/async-main-is-available-but-hidden/) for more details.

The project supports the Azure Media Services v3 quickstarts article:

|Project name|Article|
|---|---|
|EncodeAndStreamFiles.csproj|[Stream files](https://docs.microsoft.com/azure/media-services/latest/stream-files-dotnet-quickstart)|

## Prerequisites

To run samples in this repository, you need:

* Visual Studio 2017 or Visual Studio Code
* An Azure Media Services account. See the steps described in [Create a Media Services account](https://docs.microsoft.com/azure/media-services/latest/create-account-cli-quickstart).

## NuGet packages 

The following NuGet packages were added to the project: 

|Package|Description|
|---|---|
|Microsoft.Azure.Management.Media|Azure Media Services SDK. <br/>To make sure you are using the latest Azure Media Services package, check [Microsoft.Azure.Management.Media](https://www.nuget.org/packages/Microsoft.Azure.Management.Media).|
|Microsoft.Rest.ClientRuntime.Azure.Authentication|ADAL authentication library for Azure SDK for NET|
|Microsoft.Extensions.Configuration.EnvironmentVariables|Read configuration values from environment variables and local JSON files|
|Microsoft.Extensions.Configuration.Json|Read configuration values from environment variables and local JSON files
|WindowsAzure.Storage|Storage SDK|

## To run the project in the solution

* Clean and rebuild the solution.
* Add appropriate values to appsettings.json. For more information, see [Access APIs](https://docs.microsoft.com/azure/media-services/latest/access-api-cli-how-to).
