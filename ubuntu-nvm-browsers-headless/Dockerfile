FROM jolicode/nvm

# Install Ubuntu packages
RUN apt-get update && \
    apt-get install -y git xvfb firefox chromium-browser && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
