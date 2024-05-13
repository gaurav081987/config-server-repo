# config-server-repo
config server repository to store global configuration for micro-service project 
for any chnages in global repo, we have to restart the config server to reload the changes from the git and then restart the respective applications.
To resolve this issue : /refresh from actuator implementation will help to reload and restart the server each time.
