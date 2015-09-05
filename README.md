# Spring Commons Configuration (Centralized common configuration)

Technologies used
    A) Spring 4.2
    B) Apache Commons Configuration
    C) MySql
    D) Spring Integration (Apache Commons)

1. When the application is running on multiple servers, then the configurations(maintained in properties file) gets difficult
   to maintain when just few properties are changed, A new release needs to happen.
   
2. Using this application just put properties/configuration in the common database and read all the properties on serevr startup. So when the property needs to change just add/delete/update property and restart server

3. Override configurations can also be maintained, if you want a specific server to run on different configuration.

4. Supports multiple profiles/env configurations.

5. Just plugin the jar and move to centralised configuration.
