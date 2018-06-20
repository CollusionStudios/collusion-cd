# Collusion CI/CD

CI/CD process using Jenkins and Docker

#### Spin up

    $ docker-compose -p jenkins up -d

#### Spin down

    $ docker-compose -p jenkins stop

#### Remove images

    $ docker-compose -p jenkins down --rmi all

#### Don't forget the .env file

    with the following values
    ```
      JENKINS_PASS=...
      JENKINS_USER=...
    ```

    Find the values from Azure


## Configuration As Code

Jenkins' configuration is being configurated by the `jenkins.yaml` file under `casc_configs` folder.

Find all the available options under `http://localhost:8080/configuration-as-code/reference`.
