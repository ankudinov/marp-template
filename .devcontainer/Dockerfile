FROM mcr.microsoft.com/devcontainers/javascript-node:20-bullseye

COPY ./carbon-convert /bin/carbon-convert
RUN chmod +x /bin/carbon-convert

USER node
RUN npm i -g carbon-now-cli
