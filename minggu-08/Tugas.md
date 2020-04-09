# TUGAS

## DOCKER ECOSYSTEM 
>![img](/minggu-08/tugas1.jpg)

## DESCRIPTION
>You may notice a swarm of whales here plays nice with others. However, since the advent of containers, people have been looking for tools to efficiently orchestrate a huge number of them. The Docker team addressed this necessity with the release of Docker Swarm, hereinafter Swarm, one of the pieces of the Docker ecosystem, in 2015, alongside with Docker Machine and Docker Compose. The preceding image shows the simplified Docker Ecosystem, which consists of Docker Machine provisioning a new Docker-ready machine, then a set of machines will be formed into a Docker Swarm cluster. Later we will be able to use Docker Compose to deploy containers to the cluster, as if it were a normal Docker Engine.

>The plan to make a cluster management system, natively, for Docker started in early 2014, as a communication protocol project called Beam. Later, it was implemented as a daemon to control heterogeneous distributed systems with the Docker API. The project had been renamed to libswarm and Swarmd is its daemon. Keeping the same concept of allowing any Docker client to connect to a pool of Docker Engines, the third generation of the project had been re-designed to use the same set of Docker Remote APIs and renamed to "Swarm" in November 2014. Basically, the most important part of Swarm are its remote APIs; the maintainers work hard to keep them 100% compatible with every version of Docker Engine. We'll call the first generation of Swarm as "Swarm v1".

>In February 2016, after the core team found the scaling limitation of the centralized service, Swarm has been internally redesigned again as swarm.v2. This time, a decentralized cluster design has been taken into account. In June 2016, SwarmKit had been released as the orchestration toolkit for distributed service at any scale. Docker announced that SwarmKit was merged into Docker Engine at DockerCon 2016. We'll refer to this version of Swarm as "Swarm v2"  or "Swarm mode".

>As we'll see later, these three musketeers (Docker Swarm, Docker Machine, and Docker Compose) operate best when together and they are so seamlessly intertwined with each other that it is almost impossible to think of them as single pieces.

>However, even despite this Machine and Compose are really direct in their goals and easy to use and understand, Swarm is a tool that indeed deserves a book for itself.

>With Docker Machine, you can provision machines, both virtual and physical, on a number of cloud platforms as well as bare metal machines to run Docker containers. With Docker Compose, you can define Dockerfiles on steroids, by describing behaviors with the easy yet powerful syntax of YAML and launch applications by just "composing up" these files. Swarm is a powerful clustering tool that requires to be studied more in depth.