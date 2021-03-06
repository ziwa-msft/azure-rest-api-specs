# Azure NetApp Files

> see https://aka.ms/autorest

This is the AutoRest configuration file for Azure NetApp Files.



---
## Getting Started
To build the SDK for Azure NetApp Files, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration



### Basic Information
These are the global settings for the Azure NetApp Files API.

``` yaml
openapi-type: arm
tag: package-2017-08-15
```


### Tag: package-2017-08-15

These settings apply only when `--tag=package-2017-08-15` is specified on the command line.

``` yaml $(tag) == 'package-2017-08-15'
input-file:
- Microsoft.NetApp/preview/2017-08-15/netapp.json
```


---
# Code Generation


## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python
  - repo: azure-sdk-for-net
```


## C#

See configuration in [readme.csharp.md](./readme.csharp.md)

## Python

See configuration in [readme.python.md](./readme.python.md)
