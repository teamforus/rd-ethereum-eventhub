FROM node:carbon

WORKDIR /usr/db-api

COPY ./package*.json ./
RUN npm install

COPY ./config.json ./
COPY ./server.js ./

CMD ["npm", "start"]