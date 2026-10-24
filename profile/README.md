# Athy Labs

**Athy** stands for *Automated Hydroponics*. This org holds Jean-Paul Thorne's earlier work from 2019 to 2023, kept here as a record. Current work lives at **[Lilly Labs](https://github.com/lilly-labs)** ([lillylabs.co.za](https://lillylabs.co.za)).

The story behind these repos: **[buildingthingswith.net/athy-labs](https://buildingthingswith.net/athy-labs/)**

## The hydroponics platform

| Repo | What it is |
|---|---|
| `athy-micro-device` | ESP32 sensor firmware, written in C# on .NET nanoFramework |
| `athy-collection-device` | .NET service on a Raspberry Pi that collects readings from the sensors |
| `athy-gateway-api` | .NET gateway API with PostgreSQL that receives device data |
| `athy-hosted-service` | Scheduled background jobs, such as database clean-up |
| `athy-component` | Shared .NET library for API responses, error handling and data access, published as a NuGet package |
| `athy-infra` | Terraform and Vault for the cloud environment |
| `athy-project-docs` | Architecture diagrams and setup notes |

## The code generator

| Repo | What it is |
|---|---|
| `athy-generator` | Turns an OpenAPI spec into a working .NET Web API solution. Console tool, API and Azure deployment |
| [`athy-templates`](https://github.com/athy-org/athy-templates) | The `dotnet new` templates the generator fills in |
| [`athy-static-web`](https://github.com/athy-org/athy-static-web) | Landing page for the generator, live as an archived showcase at [athy-generator.lillylabs.co.za](https://athy-generator.lillylabs.co.za) |

Most of these repos are private for now. The tech is dated, and some of it may come back to life.