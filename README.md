# Catálogo Docker Compose 

Esse repositório é o que eu uso para versionar as stacks que eu mais utilizo para estudo e testes, quer usar como base ? Faz um fork e vamos #rumoalite !!!

## Quer aprender Docker ?

Se você quiser aprender Docker do zero ao avançado e dominar a principal ferramenta do mercado de TI, confere o Docker Pro:

[https://dvpro.co/catalogo-docker-compose](https://dvpro.co/catalogo-docker-compose)

## Script Docker Clear

Com esse script você consegue limpar todo o seu Docker

```bash
#!/bin/bash

docker container rm -f $(docker container ls -qa)
docker image rm -f $(docker image ls -q)
docker network rm -f $(docker network ls -q)
docker volume rm -f $(docker volume ls -q)
docker system prune --all --force
```