# Cells Enterprise distribution API client

[Go](https://golang.org/) SDK for **Cells Enterprise** REST API. Please check [Cells SDK GO](https://github.com/pydio/cells-sdk-go) for accessing the core APIs of Pydio Cells (home edition).

For more information, please visit [https://pydio.com/en/docs/developer-guide/cells-sdk-go](https://pydio.com)

This SDK is generated automatically using [go-swagger](https://github.com/go-swagger/go-swagger) from the OpenAPI specification of Cells Enterprise Rest API. 

Last updated for version 3.0.1 of the Cells Enterprise API.

## Usage

The library is publicly available, simply:

```sh
go get github.com/pydio/cells-enterprise-sdk-go 
```

and import necessary sub packages in your code.

As this library only adds Enterprise Specific endpoints to the core Cells API, you can rely on the `transport` package of the Cells SDK for authentication and file transfers.

## Versioning policy

To workaround the obligation of adding v2, v3, ...  subfolders at each new major version, we stay at version 1 in this (very stable) repository.

For better compatibility, the minor version of the SDK you are using should match the major version of your running Cells instance.  
For instance use Sdk Go v1.3.x with a recent v3 server. 

## License

This library is licensed under Apache V2.0 license.
