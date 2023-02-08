# Min.io Docker Compose File
## Introduction
n 2006, Amazon launched a service to store files in the cloud. The service is called S3, or Simple Storage Service, has since become one of the most popular ways to scale your datastorage needs in the cloud. Since then, there have been a lot of different competitors on the market to make S3-compatible services that have different underlying architectures, different business models or, most interesting for me, are selfhostable. 

This repository contains an example `docker-compose.yml` file you can use as an example to selfhost Min.io .

## Installing Min.io
Installing min.io is very easy: just download the `docker-compose.yml` file and run `docker-compose up -d` to start it up. You can access the console in your browser via `http://<your-ip>:9090/` and the API through `https://<your-ip>:9000/`. 

## Read more
You can read everything about this file and why I made this on my blog [selfhostedheaven.com](https://selfhostedheaven.com/posts/20230208-self-host-min-io/).
