# eureka-cli
A prototype CLI for managing a Spring Cloud Services Service Registry service instance
```
NAME:
   eureka - interact with a Service Registry Service Instance as a bound application
USAGE:
   eureka command cf-app-name [status]
COMMANDS:
   registry        - Dump the entire registry as JSON. The server responds with cached
                     data that is refreshed every 30 seconds.
   apps            - Display the registry as a table. Also cached data.
   override-status - Override the status of the bound app's instances. Affected instance
                     records are returned, which are not cached data.
   delete-override - Delete the status override, optionally setting the status of the bound
                     app's instances, or allowing it to be determined automatically.
                     Affected instance records are returned, which are not cached data.
   deregister      - Remove the instance records of the bound app's instances
STATUSES:
   UP - Ready to receive traffic
   DOWN - Do not send traffic - healthcheck callback failed
   STARTING - Do not send traffic - initializations to be done
   OUT_OF_SERVICE - Intentionally shutdown for traffic
   UNKNOWN - Do not send traffic - status to be determined automatically
```
