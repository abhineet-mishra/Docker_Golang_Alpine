## A basic GoAPI running on Alpine Docker

### Steps to install docker (for centos)
   1. sudo docker build -t dockername/docker .
   2. sudo docker run -p  portnumber:exposed_port_in_docker  -d  dockername/docker 

### For using Gorilla MUX router based Go API

   1. sudo docker build -t godocker/docker .
   2. sudo docker run -p 8080:9030 -d godocker/docker

### For using Iris framework based Go API
 
   In dockerfile uncomment the line number 12 and comment the line number 13. Modify the line number 17 "CMD cd /src && go run ./golan.go"
   1. sudo docker build -t godocker/docker .
   2. sudo docker run -p 8080:9040 -d godocker/docker
   


   
 
   
   
