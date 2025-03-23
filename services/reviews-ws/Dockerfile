FROM node:lts

WORKDIR /usr/src/app

COPY package.json .

RUN npm install

COPY index.js .
COPY reviews.graphql .

CMD [ "node", "index.js" ]