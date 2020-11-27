# Basic docker server stack containing:
* Nginx
* PHP 7.4 with symfony installer
* MYSQL 8
* NODE 
### To build all docker containers, run: 
1. cd docker

2. docker-compose up -d --build

### To connect and exec commands in container

docker exec -it {container name} bash

example: 
docker exec -it php74-container bash

