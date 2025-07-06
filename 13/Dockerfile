FROM node:18-alpine

RUN apk add --no-cache git

RUN git clone https://github.com/eMahtab/node-express-hello-world.git /app

WORKDIR /app

RUN npm install

# Corrige o arquivo main do package.json
RUN sed -i 's/"main": "server.js"/"main": "app.js"/' package.json

EXPOSE 3000

CMD ["npm", "start"]
