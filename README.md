# git-composefiles

docker-compose based setup and deployment information for the git-workshop.

## Usage

- Ensure the network 'gittalk' is created
  - if not, run: `docker network create gittalk`
  - this network is used to connect the clients to the internet
- Ensure the network 'gittalk-int' is created
  - if not, run: `docker network create --internal gittalk-int`
  - this network is used for connections between the clients
- run: `docker-compose up`
- done :)

## Done

- Services
- Docker images

## TBD

- Authorization
- Resource limits
- PKI
- Deploy frontends
