
# Build a basic Hello World
## References
* express:  https://expressjs.com/en/starter/generator.html

## Commands to create and run application
* Create a git repository Reference: https://github.com/CODevOp/express-rest-API
* install express command line globally

    ``` Powershell
    npm install express-generator -g
    ```
* Create express application
    ``` Powershell
    express express-GreetingApp
    cd express-GreetingApp
    ```

* install dependencies:
    ``` Powershell
    npm install
    ```

* watch the output and run the following if required
    ``` Powershell
    npm audit fix
    ```

* run the application    
    ``` Powershell
    #run the app from cmd:
    SET DEBUG=express-greetingapp:* & npm start
    
    #run the app from Powershell
    $ENV:DEBUG = "express-greetingapp:*"; npm run start
    ```