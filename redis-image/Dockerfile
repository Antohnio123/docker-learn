# Use a default image as a base
FROM alpine


# Download and install a dependency
RUN apk add --update redis
RUN apk add --update gcc


# Tell what to do as it starts as a container (set a primary Command)
CMD ["redis-server"]

