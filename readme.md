# docker-postgis

A simple docker container that runs PostGIS

## Building the image

```shell
docker-compose build --no-cache
```

--no-cache is optional. Do not use cache when building the image, if you need to completely rebuild the image you can use this otherwise it was optional.

## Running the container

```shell
docker-compose up -d
```

-d will run the container in background
## Stoping the container

```shell
docker-compose down
```