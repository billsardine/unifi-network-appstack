# Unifi Network Application Appstack

This is an appstack for the unifi network applicaiton based on the work by the folks at Linuxserver.io [https://www.linuxserver.io/]

This appstack has both mongodb service and the Unifi Network Application.  Please make sure to set the values in both the compose file and the init-mongo.js file for:

```
MONGO_DBNAME
MONGO_USER
MONGO_PASS
```
init-monog.js will only be run on the inital startup of the stack so if there is an error you will need to destroy the config directory and start again.

