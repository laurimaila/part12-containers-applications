FROM node:16

WORKDIR /usr/src/app

COPY . .

RUN npm ci

ENV DEBUG=docker-testi:*

USER node

CMD npm start

