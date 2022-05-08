# docker compose for a local graph-node

Forked from https://github.com/graphprotocol/graph-node/blob/master/docker/docker-compose.yml

## Prerequisites
- [docker](https://docs.docker.com/engine/install/) 
- [docker compose](https://docs.docker.com/compose/install/)

## Steps to start a local node
0. Clone this repo
1. Rename sample.env to .env and edit the API URL and Postgresql password
2. In a terminal, change path to the cloned repo and type `docker compose up`

## References
- More about the docker image: https://github.com/graphprotocol/graph-node/tree/master/docker
- Deploy subgraph to a local node: https://github.com/graphprotocol/graph-node
