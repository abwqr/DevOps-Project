FROM node:20.8.0-alpine3.18

# Create app directory
WORKDIR /app

EXPOSE 8080

COPY frontend/package*.json ./

RUN npm install

RUN apk add curl 

COPY frontend/ .

CMD [ "npm", "start" ]
