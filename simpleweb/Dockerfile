# Specify base Image
FROM node:alpine

# Directory where you gonna put your app
WORKDIR /usr/app

#Copy build files to container
COPY ./package.json ./
# Install some dependencies
RUN npm install

COPY ./ ./

# default command
CMD ["npm", "start"]

