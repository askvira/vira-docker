# Use Ubuntu 16.04 LTS
FROM ubuntu:16.04

# Install Ubuntu packages
RUN apt-get update
RUN apt-get install -y git curl build-essential libssl-dev xvfb firefox chromium-browser

# Get NVM
RUN curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash

# Set NVM path
ENV NVM_DIR=/root/.nvm

# Install NVM
RUN . $HOME/.nvm/nvm.sh

