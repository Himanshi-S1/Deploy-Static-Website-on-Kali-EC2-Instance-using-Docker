# Deploy-Static-Website-on-Kali-EC2-Instance-using-Docker

#Setup Kali Linux

1) sudo apt-get update && apt-get upgrade

2) docker images

#Add the preferred Web server and the path to be copied (where the index.html file is stored in Kali Linux Machine) in the Dockerfile

3) nano Dockerfile


Dockerfile can be look like:

FROM nginx

COPY . /home/kali/DockerFiles/demo-for-docker/index.html





