# Golang Basic Web-Application Template

[This Golang Basic Web-Application Template is only a recommendation]

- The **cmd** directory contains application specific code for the executable applications in the project. In this template the web application lives under cmd/web


- The **internal** directory contains non application specific code. Like helpers or a SQL database model. 
*Note: This directory name carries a special meaning and behavior in Go: any packages which lives under this directory can only be imported by code inside the parent of the internal directory!*


- The **ui** directory will contain the user-interface such as the html. Static files are located in **static** (like CSS and images).


## How to use it?

Just initialise it and start to code
- go mod init example/projectname