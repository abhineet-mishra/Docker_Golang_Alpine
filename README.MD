## A basic GoAPI running on Alpine Docker

### Steps to install docker (for centos)
   1. sudo docker build -t dockername/docker .
   2. sudo docker run -p  portnumber:exposed_port_in_docker  -d  dockername/docker 
 
 Example
   sudo docker build -t godocker/docker .
   sudo docker run -p 9040:4000 -d godocker/docker
 
   
   
