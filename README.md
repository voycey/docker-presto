# Dockerized [PrestoDB](https://prestodb.io/)

## How to use

This repo comes with default config to spin up:

- presto
- postgresql + postgis and its connector

So you only have to `docker-compose up` and use [CLI](https://prestodb.io/docs/current/installation/cli.html)
to access the presto container at `docker-host:8080`.

Note that postgis is set with defaults and no password, they are exposing default ports. 
