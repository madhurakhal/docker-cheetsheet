# docker-cheetsheet

### Stoping all the running containers
`docker stop $(docker ps -a -q)`

### Delet all the stopped containers
`docker rm $(docker ps -a -q)`
