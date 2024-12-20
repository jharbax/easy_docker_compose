# README EASY AND EMPTY docker-compose.yaml 📜

Welcome to EasyDockerCompose! Here you'll find default templates of docker-compose for multiple solutions

## General

You can execute the following command in each folder to run a docker container:

```
$> docker compose up -d
```

To kill the containers running, you can execute:

```
$> docker compose down
```

You must run these commands inside each folder with docker-compose.yaml

If you change any variable in docker-compose.yaml, to run the new configuration, you can use this command:

```
$> docker compose up -d --force-recreate
```

## postgres

You can change the postgres credentials manipulating the variables POSTGRES_USER and POSTGRES_PASSWORD. It's possible to remove then, except for POSTGRES_PASSWORD that is the minimal required configuration.

# Contact

Jonatas Harbas (jharbax) - jharbax@gmail.com
