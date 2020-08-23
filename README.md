## INFORMATION
This repository contains a cloud deployment configuration to deploy rasa x using a docker swarm stack under traefik reverse proxy.

## GETTING STARTED

### TRAEFIK
Build the `traefik` directory using the `make` command. There is a readme there with more information about building it.

### RASA
Build the `rasa` directory using the `make` command. Once the `docker-compose/yml` has been generated deploy it on docker using docker swarm stack. You may need to create a docker swarm node & network if necessary.

