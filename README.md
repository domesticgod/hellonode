# hellonode
Hellow world in node.js using Docker.

You may need to install Node.js and express on your machine but hopefully the docker image solves this

Requires docker already installed and running on the build machine

Build docker image with
docker build -t domesticgod/hellonode .

Run with 
docker run -p 49160:8080 -d domesticgod/hellonode 

In your browser go to http://localhost:49160