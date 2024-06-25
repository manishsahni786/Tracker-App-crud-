FROM node

WORKDIR /Tracker-App

COPY package.json package.json
COPY package-lock.json package-lock.json

RUN npm install


COPY . .

ENTRYPOINT [ "node", "server.js" ]
