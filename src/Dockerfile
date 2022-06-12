FROM node:17.6.0

WORKDIR /app

COPY ./package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node" , "server.js"]