# Use the lighter Java 17 image to reduce disk usage when building
FROM mcr.microsoft.com/devcontainers/java:1-17-bullseye

# Install Graphviz, curl and Node.js for JHipster
RUN apt-get update \
    && apt-get install -y graphviz curl \
    && rm -rf /var/lib/apt/lists/* \
    && curl -fsSL https://nodejs.org/dist/v18.20.0/node-v18.20.0-linux-x64.tar.xz -o node.tar.xz \
    && tar -xJf node.tar.xz -C /usr/local --strip-components=1 \
    && rm node.tar.xz

# Install JHipster after Node.js is available
RUN npm install -g generator-jhipster
