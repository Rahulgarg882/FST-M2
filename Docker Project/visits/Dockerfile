# set the base image
FROM node:18-alpine

# set the working directory
WORKDIR /usr/app

#copy package.json into the container
COPY ./package.json ./

# install the dependencies
RUN npm install

#Copy the rest of the files
COPY ./ ./

# start the web server
CMD ["npm", "start"]