# Docker

% docker, container

#plateform/multiple #target/local #cat/DOCKER

## Remove all images without at least one container associated to them
docker image prune -a

## Launch command in a docker container
docker exec -it <container> <command>

## Displays CPU and memory usage statistics of running Docker containers or all containers (if specified) in a table format, showing container ID, CPU percentage, and memory usage
docker stats --no-stream --format "table {{.Container}}\t{{.Name}}\t{{.CPUPerc}}\t{{.MemUsage}}" <container|--all>

% docker-compose

#plateform/linux #target/local #cat/DOCKER

## Builds, (re)creates, starts, and dettaches to containers for all services
docker compose up -d && docker compose logs -f

#plateform/multiple #target/local #cat/DOCKER

## Stops containers and removes containers, networks created by up
docker compose down