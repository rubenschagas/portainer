# A PORTAINER AUTOMATED DEPLOYMENT

## TABLE OF CONTENTS

[OVERVIEW](#overview)

[PRE REQUISITES](#prerequisites)

[USE CASES](#use-cases)

[ACCESSING AND CONFIGURATION THE GUI](#accessing-and-configuration-the-gui)

## OVERVIEW

The objective of this README.md document file is to provide help on how to run the automated deployment of a [local] containerized Portainer service using a Docker Compose yml file, a powerful, open source toolset based in a gui that allows you to easily build and manage containers in Docker.

## PREREQUISITES

```
1. "docker": "24.0.2";
2. "docker compose": "2.18.1".
```

Please see the [Oficial Documentation](https://hub.docker.com/r/postgis/postgis).

## USE CASES

```
docker-compose -f docker-compose-portainer.yml pull
docker-compose -f docker-compose-portainer.yml up -d
```

## ACCESSING AND CONFIGURATION THE GUI

1. Using a browser, access the address: [`localhost:9443`];
2. Configure a admin user;  
3. Using the wizard, configure the [local] environment through a socket connection, as follows:

![](./assets/readMeMd/portainer1.png)

![](./assets/readMeMd/portainer2.png)

![](./assets/readMeMd/portainer3.png)

See also:

[Oficial Instalation Guide](https://docs.portainer.io/start/install-ce)

[Oficial Documentation](https://docs.portainer.io/)