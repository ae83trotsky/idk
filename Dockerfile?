FROM node:20-alpine

RUN apk add --no-cache git

RUN git clone https://github.com/ae83trotsky/idk.git

WORKDIR /idk

RUN npm install

CMD npm start
