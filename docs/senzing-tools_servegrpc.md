## senzing-tools servegrpc

Start a gRPC server for the Senzing SDK API

### Synopsis


Start a gRPC server for the Senzing SDK API.
For more information, visit https://github.com/Senzing/servegrpc
	

```
senzing-tools servegrpc [flags]
```

### Options

```
      --database-url string                URL of database to initialize [SENZING_TOOLS_DATABASE_URL]
      --enable-g2config                    Enable G2Config service [SENZING_TOOLS_ENABLE_G2CONFIG]
      --enable-g2configmgr                 Enable G2ConfigMgr service [SENZING_TOOLS_ENABLE_G2CONFIGMGR]
      --enable-g2diagnostic                Enable G2Diagnostic service [SENZING_TOOLS_ENABLE_G2DIAGNOSTIC]
      --enable-g2engine                    Enable G2Config service [SENZING_TOOLS_ENABLE_G2ENGINE]
      --enable-g2product                   Enable G2Config service [SENZING_TOOLS_ENABLE_G2PRODUCT]
      --engine-configuration-json string   JSON string sent to Senzing's init() function [SENZING_TOOLS_ENGINE_CONFIGURATION_JSON]
      --engine-log-level int               Log level for Senzing Engine [SENZING_TOOLS_ENGINE_LOG_LEVEL]
      --engine-module-name string          Identifier given to the Senzing engine [SENZING_TOOLS_ENGINE_MODULE_NAME] (default "initdatabase-1678311446")
      --grpc-port int                      Port used to serve gRPC [SENZING_TOOLS_GRPC_PORT] (default 8258)
  -h, --help                               help for servegrpc
      --log-level string                   Log level of TRACE, DEBUG, INFO, WARN, ERROR, FATAL, or PANIC [SENZING_TOOLS_LOG_LEVEL] (default "INFO")
```

### SEE ALSO

* [senzing-tools](senzing-tools.md)	 - Tools to help use the Senzing API
* [senzing-tools servegrpc completion](senzing-tools_servegrpc_completion.md)	 - Generate bash completion for the command
* [senzing-tools servegrpc docs](senzing-tools_servegrpc_docs.md)	 - Generate documentation for the command

###### Auto generated by spf13/cobra on 8-Mar-2023
