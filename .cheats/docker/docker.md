# Docker

% docker, container

#plateform/multiple #target/local #cat/UTILS 

## Remove all images without at least one container associated to them
docker image prune -a

# launch command in a docker container
docker exec -it <container_name> <command>

% docker-compose

# Builds, (re)creates, starts, and dettaches to containers for all services
docker compose up -d && docker compose logs -f

# Stops containers and removes containers, networks created by up
docker compose down