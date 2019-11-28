# Learning Docker 

> This repo is meant to be a guide for you to start learning and using docker! WIP :construction:

## Installation 
**For Ubuntu**

```bash
sudo apt-get remove docker docker-engine docker.io containerd runc
sudo apt-get update
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo apt-key fingerprint 0EBFCD88
sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
sudo usermod -aG docker $USER 

```

## Learning resources 


- [Play with Docker](https://training.play-with-docker.com/)
- [Docker Memrise](https://www.memrise.com/course/961872/docker-3/)
