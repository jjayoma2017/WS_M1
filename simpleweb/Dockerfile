# Sepecify a base image
FROM node:16-alpine

WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command on start up
CMD [ "npm", "start" ]