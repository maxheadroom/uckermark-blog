# Blog Setup
This repository documents the setup of our blog using WordPress. The intention of this document is, that another person with enough technical base knowledge would be able to replicate the setup or restore the setup from this repository.

I expect the reader to be savvy with the following technologies:
  * Docker Containers general concepts
    * Docker Compose
  * WordPress general setup/concepts
  * Apache Webserver general setup/concepts
  * MySQL Database general setup/concepts
## Prerequisites
The setup expects a machine with a working Docker/Docker compose setup and sufficient CPU/Memory. It has been tested on Linux only so far.
The current setup also uses a Traefik Proxy as reverse Proxy in front of the setup to handly SSL termination and some temporary authentication. This might not be needed in a later setup and can be replaced by any Reverse Proxy or completely removed. The SSL Termination and Certifcate handling must be re-implemented then. 
