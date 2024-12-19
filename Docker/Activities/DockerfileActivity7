#set the base image
FROM docker.io/node:18-alpine

#Create a Work Directory
WORKDIR usr/app

#Copy the files into container

COPY ./ ./
# Download and install a dependency
RUN npm install
 
# Tell the image what to do when it starts
# as a container
CMD ["npm", "start"]