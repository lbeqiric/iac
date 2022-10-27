# Base Docker Image

Create a basic, Ubuntu based docker image that can be used to create cotnainers where Confluent (or other) components can be deployed into, removing the need to create expensive VMs through public cloud providers.

## Image Creation Steps

Clone Repository

    git clone https://github.com/lbeqiric/iac.git

Change Directory

    cd ../docker

Build Docker Image & Push (optional)

    docker build -t vdesabou/cp-ansible-playground-ubuntu:latest .
    docker push vdesabou/cp-ansible-playground-ubuntu:latest