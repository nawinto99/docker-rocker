# Docker Rocker

##### Build Docker Image:
> docker build . -t nawinto99/docker-rocker
##### Check Docker Images: 
> docker images
##### Run Docker Image:
> docker run -p 8080:8080 -d nawinto99/docker-rocker
##### Check Containers: 
> docker ps
##### Check Container Logs: 
> docker logs <container id>
##### Enter Into Container:
> docker exec -it <container id> /bin/bash
##### Test Application:
> curl -i localhost:8080

