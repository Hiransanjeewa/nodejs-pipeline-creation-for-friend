# Fetching the latest node image on alpine linux
FROM node:alpine AS development

# Declaring env
ENV NODE_ENV development
# Setting up the work directory
WORKDIR /express-docker

# Copying package.json and package-lock.json
COPY package.json package-lock.json /express-docker/

# Copying all the files in our project
COPY . .

# Installing dependencies
RUN npm install

# Exposing server port
EXPOSE 5000

# Starting our application
CMD npm run dev





# Fetching the latest node image on alpine linux
FROM node:alpine AS development

# Declaring env
ENV NODE_ENV development

# Setting up the work directory
WORKDIR /app

# Copying package.json and package-lock.json
COPY package.json package-lock.json /app/


