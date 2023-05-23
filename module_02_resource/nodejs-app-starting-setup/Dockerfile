# base image
FROM node

# set working directory
# now all of subsequent actions will be done in this directory
WORKDIR /app

COPY package.json /app

# install all the dependencies of node application
RUN npm install

# copy sources to container
COPY . /app
# same with COPY . ./

EXPOSE 80

# run this when the container is getting started
CMD ["node", "server.js"]
