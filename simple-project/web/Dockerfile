# Specify a base image
FROM node:14-alpine

WORKDIR /usr/app

# Install some depenendencies
COPY package.json ./
COPY index.js ./
RUN npm install

# Default command
CMD ["npm", "start"]