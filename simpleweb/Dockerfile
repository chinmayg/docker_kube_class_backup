# Specify a base image
FROM node:alpine

# Specified work directory
WORKDIR /usr/app

# Copy files needed for the build process
COPY ./package.json ./

# Install Dependencies
RUN npm install

COPY ./ ./

# Default Command
CMD [ "npm", "start" ]
