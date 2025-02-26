# Question 2 Midterm Devops

In this repository, I have provided:
* The base files from `example-1` of Chapter 4 from Bootstrapping Microservices 2nd edition.
* The modified `docker-compose.yaml` to add new replicas of `video-streaming` service.
* An `nginx.conf` configuration file to setup NGINX.
    * Redirects from HTTP to HTTPS
    * Uses localhost self signed certificate.
    * Proxies requests from `/video` to Docker containers.
    * Uses Round-Robin load balancing for `/video`.