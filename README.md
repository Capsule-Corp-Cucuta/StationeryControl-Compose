# StationeryControl-Docker-Compose

This project generate the infrastructure of Stationery Control Project in a Docker architecture.

## Preparation

First we need download the follow repositories:

[Discovery-Service](https://github.com/Capsule-Corp-Cucuta/StationeryControl-Discovery-Service)

[ReverseProxy-Service](https://github.com/Capsule-Corp-Cucuta/StationeryControl-ReverseProxy-Service)

[User-API](https://github.com/Capsule-Corp-Cucuta/StationeryControl-User-API)

[Certificate-API](https://github.com/Capsule-Corp-Cucuta/StationeryControl-Certificate-API)

[Delivery-API](https://github.com/Capsule-Corp-Cucuta/StationeryControl-Delivery-API)

In the root folder where we download the repositories we download this repository. Should be like the follow example:

.
├── StationeryControl-Discovery-Service/
│   ├── src/
│   │   └── ...
│   ├── .gitignore
│   ├── Dockerfile
│   ├── LICENSE
│   ├── README.md
│   └── pom.xml
├── StationeryControl-ReverseProxy-Service/
│   ├── src/
│   │   └── ...
│   ├── .gitignore
│   ├── Dockerfile
│   ├── LICENSE
│   ├── README.md
│   └── pom.xml
├── StationeryControl-User-API/
│   ├── src/
│   │   └── ...
│   ├── .gitignore
│   ├── Dockerfile
│   ├── LICENSE
│   ├── README.md
│   └── pom.xml
├── StationeryControl-Certificate-API/
│   ├── src/
│   │   └── ...
│   ├── .gitignore
│   ├── Dockerfile
│   ├── LICENSE
│   ├── README.md
│   └── pom.xml
├── StationeryControl-Delivery-API/
│   ├── src/
│   │   └── ...
│   ├── .gitignore
│   ├── Dockerfile
│   ├── LICENSE
│   ├── README.md
│   └── pom.xml
├── docker-compose.yml
├── LICENSE
└── README.md

## Build

Run `docker-compose build` for build the images.

## Start the server 

Run `docker-compose up -d` for start the Stationery Contol Project.
