# Use an existing docker image as base
FROM alpine

# Download and install a dependency
RUN apk add --update redis

RUN apk add --update gcc

# Tell the image wha to do when it starts as container
CMD ["redis-server"]
