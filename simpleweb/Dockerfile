# Use a default image as a base
FROM node:alpine
WORKDIR /usr/app/


# Copy exact 1 file inside the container
COPY ./package.json /usr/app/
# Download and install a dependency
RUN npm install

# Copy all the rest building context inside the container
#(First ./ means building context, second ./ means WORKDIR)
COPY ./ ./


# Tell what to do as it starts as a container (set a primary Command)
CMD ["npm", "start"]

