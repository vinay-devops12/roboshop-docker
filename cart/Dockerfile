FROM node:20
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY *.js .
EXPOSE 8080
CMD ["node", "server.js"]