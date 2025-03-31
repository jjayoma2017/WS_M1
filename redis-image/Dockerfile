# Use an existing docker image as a base
FROM alpine
# Download and install as dependency
RUN apk add --update redis
# Tell the image what to do when it starts a a container
CMD ["redis-server"]