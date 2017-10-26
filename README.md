# Cognitive Genie Services Parent POM

## Summary
Parent pom project to control dependency version and default plugin configurations.
This pom needs to be in your repository if you project uses it.

## Description
Decouples Spring version and other dependency versions from the Services. Allows for all services to be deployed in a coupled fashion, same configuration of dockerfile to be applied across all of the services. 
Provides standard plugin configuration to be used across all child services.

## Features
- Hide Spring dependencies version
- Provide standard plugin version
- Centralise dependency and plugin repositories


## Installation and Setup	
Run: mvn install to install this pom in your repository, if you use command line
From Eclipse/STS, run using Run menu and select mvn install goal.


## Configuration Parameters
docker.image.prefix, docker.repository.name   provide the docker repo name to upload the docker images to, when pushed.
