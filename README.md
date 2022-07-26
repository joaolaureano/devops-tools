# DevOps Tools

This repository was created to study and ensharpen my DEVOPS skills, such as automation and pipeline

## Tools being used
### Terraform
- Heroku<br>
As for now, the Heroku project only contain an base app and a database integration.
<br>
In order to use this as template, you need to specify a <i>terraform.tfvars</i> file for some variables. 
<br>
As for now, those are...
<br>
```
    heroku_develop_app
    heroku_develop_database
    heroku_region
    heroku_app_buildpacks
```
After specifying it, you need to use <i>terraform apply </i> command.


### Github actions
You will find templates for Github Actions that are used by me in my personal projects
#### Templates
- NodeJS + Test<br>
This is a simple template for NodeJS and test implementation. Planning to add auto-deploy