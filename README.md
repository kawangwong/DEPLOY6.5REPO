This file was pushed here using git form a ubuntu image pulled from dockerhub

This container was created using the following command.

docker run -ti \
--name gitcontainer \
--volume $(pwd)/Desktop/gitstuff:/gitfolder
bash \ 
ubuntu:latest
<h1>Goal</h1>
The goal of this deployment was to:

1)Create a jenkins container that would be able to build.

2)Created a container for docker to pass through its functions as a docker cotainer for other containers to access docker's main engine.

3)Create an image file from a prebuild image using Dockerfile to deploy jenkins with blueocean integrated.

4)Used that new image in a container to hook into the container in step 2 to create a build pipeline that would allow it to access container creation capabilities for the purposes of automatically deploying jenkins-agents.
