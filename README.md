# Collusion CI/CD

CI/CD process using Jenkins and Docker

#### Spin up

    $ docker-compose -p jenkins up -d

#### Spin down

    $ docker-compose -p jenkins stop

#### Remove images

    $ docker-compose -p jenkins down --rmi all
