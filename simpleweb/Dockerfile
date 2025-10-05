# Specify a base image
FROM node:14-alpine

#copy
WORKDIR /usr/app
COPY ./package.json ./
#Install som dp
RUN npm install
COPY ./ ./

#Default command
CMD ["npm", "start"]