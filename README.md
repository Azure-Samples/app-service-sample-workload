# App Services sample workload

This GitHub repository contains a simple web application sample that connects to an Azure SQL Database. The sample application supports reference implementations of articles published in the Azure Architecture Center (AAC).

- [Baseline highly available zone-redundant web application](https://github.com/Azure-Samples/app-service-baseline-implementation)

## Features

The sample project provides the following features:

- A simple Welcome page
  ![Home Page](homePage.png)
- A product categories page to illustrate database connectivity
  ![Product Categories Page](ProductCategoriesPages.png)

## Getting Started

### Prerequisites

- [.Net 9.0](https://dotnet.microsoft.com/download/dotnet/9.0)
- [Visual Studio Community 2022](https://visualstudio.microsoft.com/vs/community/)
- [Adventureworks database example](https://learn.microsoft.com/sql/samples/adventureworks-install-configure)

### Setup Instructions

1. Install [Adventureworks database example](https://learn.microsoft.com/sql/samples/adventureworks-install-configure)
1. Get connection string and add it to appsettings.json
1. Open SimpleWebApp.sln with Visual Studio

> :warning: the repo contains an already compiled version (SimpleWebApp.zip) of the solution which is going to be used in the reference implementations.

## Contributions

Please see our [contributor guide](./CONTRIBUTING.md).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact <opencode@microsoft.com> with any additional questions or comments.

