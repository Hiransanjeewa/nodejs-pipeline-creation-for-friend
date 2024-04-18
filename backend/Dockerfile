# Fetching the minified node image on apline linux
FROM node:20.1-alpine

# Setting up the work directory
WORKDIR /express-docker

# Copying all the files in our project
COPY . .

# Installing dependencies
RUN npm install

# Starting our application
CMD [ "npm", "run", "dev" ]

# Exposing server port
EXPOSE 5000