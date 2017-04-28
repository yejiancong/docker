# docker

#delete all the containers
`docker rm -f $(docker ps -a -q)`

#delete untagged images
`docker rmi -f $(docker images --filter dangling=true -q)`
