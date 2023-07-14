# Introduction 
This repo contains a number of reusable modules that can be called from other projects. 

# Build and Test
When adding a new module or making any changes we should run 2 commands: 
`terraform fmt` - to format all the files in a module
`terraform validate` to check that the modules are syntactically valid

# Naming Conventions
## Module names
Module names should all be lower case with words separated by underscores, e.g. "resource_group". The folder should be named the same as the module. 

## Variable names
Variable names should be prefixed with the name of the resource that they belong to. E.g. they shouldn't be called "name", but instead "resource_group_name" or "app_service_name". 