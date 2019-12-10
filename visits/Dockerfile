# Base version image
FROM node:alpine

# Setting work directory
WORKDIR /app

# Installing dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command to run
CMD [ "npm", "start" ]