# Learn Traefik
This repository contains examples on using traefik reverse proxy. This repository is used as a teaching aid in the training videos about Traefik, created by Kamran. These videos are available here:

* [English Playlist: - How to Use Traefix Reverse Proxy](https://www.youtube.com/playlist?list=PLuvRKxeqrv4JxyDhH4yhDoYHuFnWQGEzI):
    * [Part 1: Introduction to Traefik](https://www.youtube.com/watch?v=CCfUrWAuxck&list=PLuvRKxeqrv4JxyDhH4yhDoYHuFnWQGEzI&index=1).
    * [Part 2: Protection for Traefik’s dashboard](https://www.youtube.com/watch?v=XIzH7hxTDu8&list=PLuvRKxeqrv4JxyDhH4yhDoYHuFnWQGEzI&index=2)
    * [Part 3: How to use HTTPS to encrypt incoming traffic](https://www.youtube.com/watch?v=9fGGddwU2w8&list=PLuvRKxeqrv4JxyDhH4yhDoYHuFnWQGEzI&index=3)
    * [Part 4: Introduction to LetsEncrypt](https://www.youtube.com/watch?v=tgh6mKj2yEw&list=PLuvRKxeqrv4JxyDhH4yhDoYHuFnWQGEzI&index=4)
    * [Part 5: How HTTP challenge works with a real web server](https://www.youtube.com/watch?v=OHDTfJzL6jg&list=PLuvRKxeqrv4JxyDhH4yhDoYHuFnWQGEzI&index=5)
    * [Part 6: How DNS challenge works](https://www.youtube.com/watch?v=wTHg7M9LY34&list=PLuvRKxeqrv4JxyDhH4yhDoYHuFnWQGEzI&index=6)
* Urdu/Hindi: 
    * [Introduction and basic setup (docker-compose)](https://youtu.be/CakHQs-GRJs) 
    * [HTTPS/SSL (docker-compose)](https://youtu.be/hwqsosJJ5S0)

The repo contains various scenarios explained with `docker-compose`. Please check the [examples/](examples/) directory for related files.

The diagrams used in these examples are available as `.xoj` and as `.pdf` in the [docs/](docs/) directory.

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

