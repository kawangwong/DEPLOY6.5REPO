This file was pushed here using git form a ubuntu image pulled from dockerhub

This container was created using the following command.

docker run -ti \
--name gitcontainer \
--volume $(pwd)/Desktop/gitstuff:/gitfolder
bash \ 
ubuntu:latest




