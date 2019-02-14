# Learn Traefik
This repository contains examples on using traefik reverse proxy. This repository is used as a teaching aid in the training videos about Traefik, created by Kamran. These videos are available here:

* English:
    * [link to be provided](link to be provided). 
* Urdu/Hindi: 
    * [Introduction and basic setup (docker-compose)](https://youtu.be/CakHQs-GRJs) 
    * [HTTPS/SSL (docker-compose)](https://youtu.be/hwqsosJJ5S0)

The repo contains various scenarios explained with Docker-Compose. Please check the [examples/](examples/) directory for related files.

The diagrams used in these examples are available as .xoj and as .pdf in the [docs/](docs/) directory.

# Topics covered in the video:
* Traefik quick start
* Understanding Traefik's behavior for an example docker-compose stack
* The `exposedByDefault` setting
* Using labels to setup frontends
* Dashboard protection with passwords
* Difference between HTTP and DNS challenge
* SSL/TLS/HTTPS with self signed certificates
* SSL/TLS/HTTPS with certificates issued by LetsEncrypt using ACME
* Difference between staging and production certificates
* LetsEncrypt's rate limits to watch for

