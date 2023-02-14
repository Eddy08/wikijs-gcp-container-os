# Instructions

## Installing docker-compose in container Optimized

DevOps Directive: <https://www.youtube.com/watch?v=GoOB8YoRSbA>

## Docker Compose YML : Change the Ports Details

<https://docs.requarks.io/install/docker#using-docker-compose>

## Steps to Run Docker container

1. Go to the folder where docker-compose.yml
2. Run Command:

 ```
 docker run 
 --rm -v /var/run/docker.sock:/var/run/docker.sock
 -v "$PWD:$PWD"
 -w="$PWd" 
 docker/compose:1.27.3 up .
 ```
