
### Deployment setup for execute-it
**Create a .env file as given in .env.example**

# Execute-It Deployment

This repository automatically pull all necessary docker containers and deploys them.


## Prerequisites

This project is built on top of docker containers. So ensure that you have
Docker and Docker Compose installed on your system For installation
instructions refer: https://docs.docker.com/install/


## Deployments


Before starting docker-compose, create a docker bridge network
```bash
docker network create -d bridge executeit
```
-------------- Enter steps here ------------------

And finally start the server 
```bash
docker-compose -f docker-compose.prod.yml up app
```

## System Architecture

![System_Architecture](https://user-images.githubusercontent.com/49340051/113477998-adb78e00-94a3-11eb-9f44-803ac84b8c24.png)



## Tech Stack Used :

![executeit](https://user-images.githubusercontent.com/49340051/113477833-6b418180-94a2-11eb-9547-75c67b96f43a.png)
