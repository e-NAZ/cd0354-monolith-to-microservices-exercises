

#Finish installing NodeJS dependencies

FROM inaz/slow-node-base

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080


CMD ["node", "server.js"]

