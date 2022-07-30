# docker_multiple_environments_project
A multi-environment project with docker compose.

In reality, we often work in multiple environments: CI, local, test, stage, production, and more. Each environment may require its own specific configurations and settings. Some services that might be needed in the local environment may not be needed in production. This is where multiple configurations come into the picture.


![image](https://github.com/pritamnikam/docker_multiple_environments_project/blob/main/multi-environment%20project%20config%20with%20docker-compose.png)


While working with multiple environments, we can define environment-specific configurations in their own compose files. The docker-compose.yml file serves as the base configuration that can contain shared configurations. The docker-compose.dev.yml file serves as the development-specific configuration. In addition, the docker-compose.ci.yml file serves as the CI environment-specific configuration, and the docker-compose.prod.yml file serves as the production environment-specific configuration.
