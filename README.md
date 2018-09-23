# hello_nodeweb
A simple Node.js web server with Visual Studio Code integration

### Source code
https://github.com/louipr/hello_nodeweb


## Project Dependencies 
* npm 
* http-server

## Install npm 
NPM can be installed from the web. 

## Add http-server to project
From the project folder execute the following command.
```
npm install http-server
```
# Create package.json
Run the following command and take all default values.
```
npm init
```
# Add start command to package.json
insert the following json entry to package.json
```
  "scripts":{
    "start":"node ./node_modules/http-server/bin/http-server"
  }
```


