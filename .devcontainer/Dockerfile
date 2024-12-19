FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install npm, Flask, and Vue.js CLI
RUN apt-get update && \
    apt-get install -y npm python3-pip && \
    pip3 install flask && \
    npm install -g @vue/cli