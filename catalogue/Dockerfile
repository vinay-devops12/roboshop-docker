FROM node:20
## create app dir then set the /app dir
WORKDIR /app              ## use workdir create dir 
COPY package.json .
COPY *.js .
## install dependencies
RUN npm install
MONGO= "true"
MONGO_URL= "mongodb://mongodb:27017/catalogue"
CMD [ "node","server.js"]