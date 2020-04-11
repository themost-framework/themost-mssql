# @themost/mssql
Most Web Framework MSSQL Adapter

## Install
    npm install @themost/mssql
## Usage
Register MSSQL adapter on app.json as follows:

    "adapterTypes": [
        ...
        { "name":"MSSQL Data Adapter", "invariantName": "mssql", "type":"@themost/mssql" }
        ...
    ],
    adapters: [
        ...
        { "name":"development", "invariantName":"mssql", "default":true,
            "options": {
              "server":"localhost",
              "user":"user",
              "password":"password",
              "database":"test"
            }
        }
        ...
    ]

If you are intended to use MSSQL data adapter as the default database adapter set the property "default" to true.

## Development
`themost-mssql` is a sub-module of [ Most Web Framework data adapters project](https://github.com/themost-framework/themost-adapters)

So, checkout parent project

    git checkout (https://github.com/themost-framework/themost-adapters.git

