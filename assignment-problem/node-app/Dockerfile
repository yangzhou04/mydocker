FROM node

WORKDIR /app/node-app

COPY package.json /app/node-app/

RUN npm install

COPY . /app/node-app/

EXPOSE 3000

CMD [ "node", "server.js" ]