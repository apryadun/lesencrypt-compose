# docker-compose example of running nginx proxy with SSL termination.
Sample project that shows how to use [docker-letsencrypt-nginx-proxy-companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion). Approach of "three containers" as described in [project Wiki](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion/wiki/Docker-Compose) was used to proxy the services in adjacent docker-compose stacks. 

Directory ```sample-service``` contains an example of some target service for testing (default nginx page). 