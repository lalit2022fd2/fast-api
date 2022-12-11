# FastAPI app with docker and docker compose
## YouTube Link: https://youtu.be/tdt2aHs87g0
## Docker commands

Check docker status
```sh
sudo service docker status
```
Build image
```sh
docker build . -t fastapi
```
List all images
```sh
docker images 
```
Run with basic docker command
```sh
docker run -d -p 90:80 fastapi
```
To List all containers
```sh
docker container ps 
```
Stop container with basic docker command
```sh
docker stop <container id>
```
To check the log
```sh
docker logs -f <container id>
```
Up the container with docker compose file
```sh
docker compose -f docker-compose.yml up -d
```
Stop the containers with docker compose file
```sh
docker compose -f docker-compose.yml down
```


