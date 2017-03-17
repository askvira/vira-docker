FROM atlassianlabs/docker-node-jdk-chrome-firefox

# Install Ubuntu packages
RUN sudo apt-get update && \
    sudo apt-get install -y git rsync && \
    sudo apt-get clean && \
    sudo rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
