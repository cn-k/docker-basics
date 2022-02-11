# specify a base image
FROM node:alpine
# install dependencies
WORKDIR /usr/app
COPY ./ ./
RUN npm install
# default command
CMD ["npm","start"]