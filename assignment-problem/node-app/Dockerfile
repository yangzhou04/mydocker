FROM node

WORKDIR /app/node-app

COPY . /app/node-app/

RUN npm install

EXPOSE 80

CMD [ "node", "server.js" ]