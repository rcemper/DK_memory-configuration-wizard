# IRIS-memory-configuration-wizard_docker
The OEX package just uses a modest IRIS instance in Docker     
It merges IPM package of MDX2JSON with some demo data    
It is built using the small [Mini-Docker-Template](https://github.com/r-cemper/mini-docker)    
### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory
```
$ git clone https://github.com/rcemper/DK_memory-configuration-wizard.git
```
To build and start the container run:
```
$ docker compose up -d && docker compose logs -f
```
To open IRIS Terminal do:
```
$ docker-compose exec iris iris session iris
USER>
```
or using **WebTerminal**
```
http://localhost:42773/terminal/
```
To access IRIS System Management Portal
```
http://localhost:42773/csp/sys/UtilHome.csp
```
### How to use it
This presents OEX package [IRIS memory configuration wizard](https://github.com/r-cemper/IRIS-memory-configuration-wizard_docker) using the actual IPM module    
All user documentation is found there in the [original repo](https://github.com/bdeboe/isc-mem-config/blob/main/README.md)     
- [Launch Configurator](http://localhost:42773/csp/mem-config/configurator.html)
