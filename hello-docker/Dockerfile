# start from a node image (alpine tag - https://hub.docker.com/_/node/tags)
FROM node:alpine
# copy all the files from the current directory into app in node image
COPY . /app
# change dir
WORKDIR /app
# run node app
CMD node app.js
