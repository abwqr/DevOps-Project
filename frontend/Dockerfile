FROM node:20.8.0-alpine3.18

WORKDIR /app

EXPOSE 8080

COPY frontend/package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "start" ]