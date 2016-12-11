# Use Ubuntu 16.04 LTS
FROM ubuntu:16.04

# Install Ubuntu packages
RUN apt-get update && \
    apt-get install -y git curl build-essential libssl-dev xvfb firefox chromium-browser && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

# Get NVM
RUN curl --location https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | sh && \
    echo "[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh" >> /etc/profile.d/npm.sh && \
    echo "[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh" >> $HOME/.bashrc

# Set NVM_DIR and PATH
ENV NVM_DIR $HOME/.nvm
ENV PATH $NVM_DIR/bin:$PATH
