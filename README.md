# Using Nginx webserver run in docker

### Build the Docker Image:
```
docker build -t my-nginx-webserver .
```
### Run the Docker Container:
```
docker run -d -p 80:80 my-nginx-webserver
```
```
http://localhost
```
### Check docker 
```
docker ps -a
```
### remove docker 
```
docker rm -f [ CONTAINER ID ]
```
### Stop Docker 
```
docker stop [ CONTAINER ID ]
```
