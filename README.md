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
* Traefik quick start (API and Dashboard) (`/api` , `/health`, etc) [https://docs.traefik.io/configuration/api/](https://docs.traefik.io/configuration/api/)
* Understanding Traefik's behavior for an example docker-compose stack
* The `exposedByDefault` setting
* Using labels to setup frontends
* Dashboard protection with passwords
* SSL/TLS/HTTPS with self signed certificates
* Introduction to LetsEncrypt, ACME, CertBot, etc
* Difference between HTTP and DNS challenge
* Difference between staging and production certificates
* LetsEncrypt's rate limits to watch for
* SSL/TLS/HTTPS certificates from LetsEncrypt
* The `acmeLogging` directive
* The `onHostRule` directive
* Example with HTTP challenge
* Example with DNS challenge

