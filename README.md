# docker-cheetsheet

### List all images
`docker image ls ` or `docker images`

### List all the containers
`docker container ls`

### Stoping all the running containers
`docker stop $(docker ps -a -q)`

### Delet all the stopped containers
`docker rm $(docker ps -a -q)`
