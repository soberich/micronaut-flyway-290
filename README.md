## Micronaut 3.3.4 Documentation

- [User Guide](https://docs.micronaut.io/3.3.4/guide/index.html)
- [API Reference](https://docs.micronaut.io/3.3.4/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/3.3.4/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

- [Azure Functions Plugin for Gradle](https://plugins.gradle.org/plugin/com.microsoft.azure.azurefunctions)
# Micronaut and Azure Function

## Prerequisites

- Gradle 5+
- Latest [Function Core Tools](https://aka.ms/azfunc-install)
- Azure CLI. This plugin use Azure CLI for authentication, please make sure you have Azure CLI installed and logged in.

## Setup

```cmd
az login
az account set -s <your subscription id>

## Running the function locally

```cmd
./gradlew clean azureFunctionsRun
```

And visit http://localhost:7071/api/micronautFlyway290

## Deploying the function

To deploy the function run:

```bash
$ ./gradlew clean azureFunctionsDeploy
```



- [Azure Functions Plugin for Gradle](https://plugins.gradle.org/plugin/com.microsoft.azure.azurefunctions)
## Feature azure-function documentation

- [Micronaut Azure Function documentation](https://micronaut-projects.github.io/micronaut-azure/latest/guide/index.html#simpleAzureFunctions)

- [https://docs.microsoft.com/azure](https://docs.microsoft.com/azure)


## Feature flyway documentation

- [Micronaut Flyway Database Migration documentation](https://micronaut-projects.github.io/micronaut-flyway/latest/guide/index.html)

- [https://flywaydb.org/](https://flywaydb.org/)


## Feature azure-function-http documentation

- [Micronaut Azure Function documentation](https://micronaut-projects.github.io/micronaut-azure/latest/guide/index.html#azureHttpFunctions)


