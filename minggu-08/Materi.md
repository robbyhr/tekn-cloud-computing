# Materi

## Docker Compose
Docker-compose provides a mechanism to bind different containers together and work in 
collaboration, as a single service (ie: It’s using the same functionality as –link command 
used to link two containers).	

## Docker Swarm
Docker-swarm is that it allows you to manage a cluster of different docker-hosts, each of 
which is running several container instances of some docker-images. We could define 
connections as overlay-networks between different containers in the swarm 
(even if they across two docker-hosts in the swarm) to connect them as a unit.

## Docker Containers
Docker containers to communicate with each other and the outside world via the host machine, 
there has to be a layer of networking involved. Docker supports different types of networks, 
each fit for certain use cases.

For example, building an application which runs on a single Docker container will have a 
different network setup as compared to a web application with a cluster with database, 
application and load balancers which span multiple containers that need to communicate 
with each other. Additionally, clients from the outside world will need to access the web 
application container. 