FROM node:20
WORKDIR /app  ## use for if create and move use this
COPY package.json .
COPY *.js .
RUN  npm install
EXPOSE 8080
CMD ["node","server.js"]

