# Use an existing docker image as base
FROM alpine

# Download and install dependency
RUN apk add --update redis

# Tell image what do when it starts as a container
CMD ["redis-server"]
