![.NET Core Build and Test](https://github.com/Cingulara/openrmf-api-controls/workflows/.NET%20Core%20Build%20and%20Test/badge.svg)

# openrmf-api-controls
This is the OpenRMF Controls API that references [this](https://nvd.nist.gov/800-53/Rev4) list of 
NIST controls but in an API that can match the CCI to NIST XML from DISA.

* GET / to get all Control Records
* GET /majorcontrols return a list of all Major Controls at a top level
* GET /{term} to get a particular Control Record
* /swagger/ gives you the API structure

## Making your local Docker image
make docker

## Moq with xUnit
* dotnet add reference ..\path-to-file\xxxxx.csproj