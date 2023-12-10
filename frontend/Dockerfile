# Use the official Node.js Alpine image
FROM node:14-alpine

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the entire application to the working directory
COPY . .

# Expose the port on which the application will run
EXPOSE 8080

# Command to run the application
CMD ["node", "app.js"]


#FROM node:20.8.0-alpine3.18

#COPY frontend/package*.json .

#RUN npm install

#COPY . .

#EXPOSE 8080

#CMD ["npm", "start", "--", "frontend/app.js"]
