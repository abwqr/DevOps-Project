FROM node:20.8.0-alpine3.18

COPY frontend/package*.json .

RUN npm install

COPY . .

EXPOSE 8080

CMD ["npm", "start", "--", "frontend/app.js"]
