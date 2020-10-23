# Ardalo Digital Platform Overview
The Ardalo Digital Platform is a blueprint how a modern digital platform may be implemented
using multiple teams and a Microservice approach.

The Platform consists of the following components:
  * [Guidelines and FAQ](https://github.com/ardalo/digital-platform-development-guide) for the development of the Ardalo Digital Platform
  * The [Platform Gateway](https://github.com/ardalo/platform-gateway) where all external traffic approaches
  * The [Frontpage Service](https://github.com/ardalo/frontpage-service) which delivers the public frontpage
  * The [Footer Service](https://github.com/ardalo/footer-service) which delivers the footer for all pages

The Ardalo Digital Platform utilizes the following external services:
  * [GitHub](https://github.com/ardalo?tab=repositories) - Source Code Hosting, Version Control System and CI/CD pipeline
  * [SonarCloud](https://sonarcloud.io/organizations/ardalo/projects) - Static Code Analysis

## Start whole Platform using docker-compose
```console
$ docker-compose build && docker-compose up
```
