FROM node:8

RUN npm install nodemon -g

WORKDIR /app

ADD ../../node-code /app

RUN npm install

ENV NAME default
RUN export NODE_ENV=default
ENTRYPOINT ["npm", "start"]
