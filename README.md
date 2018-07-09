# Collusion CI/CD

CI/CD process using Jenkins and Docker

#### Spin up

    $ docker-compose -p jenkins up -d

#### Spin down

    $ docker-compose -p jenkins stop

#### Remove images

    $ docker-compose -p jenkins down --rmi all

## Configuration As Code

Jenkins' configuration is being configured by the `jenkins.yaml` file under `casc_configs` folder.

Find all the available options under `http://localhost:8080/configuration-as-code/reference`.

*Our Dockefile is based on https://github.com/jenkinsci/docker/blob/master/Dockerfile-alpine*
