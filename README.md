# reverse-proxy 
1- clone the repository 
2- insure that docker and docker compose is installed on you machine
3- get inside the cloned folder
4- run command ( sudo docker-compose up -d )

you will end with three containers one on running on port 7000 another on 8000 and the reverse proxy container on 80

you can test first two java apps on urls (http://localhost:7000/devopsarea-1.0/  and http://localhost:8000/devopsarea-1.0/)

the reverse proxy container urls will be like below

1-http://localhost/javaapp1 --> that will redirect to the first java app container 
2-http://localhost/javaapp2 --> that will redirect to the first java app container 
3-http://localhost/bbc      --> will redirect to bbc web site
