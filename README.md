# code-server-blueprint
Blueprint for using code-server for Python development.

## Getting started

1. Start server: 
    * Without being beind a proxy: ```docker-compose up ide```
    * If behind a proxy: ```docker-compose up ide-proxy```
3. Open browser at ```http://localhost:8443/```

## Extending this bluepeint

You have numerous options to extend this blueprint:

* Add Python dependencies to ```requirements.txt```
* Add Ubuntu dependencies to ```Dockerfile```
* Install more VSCode extensions at ```Dockerfile```
* Customize VSCode settings at ```.vscode/settings.json```

## References
https://github.com/cdr/code-server
