# Use base node 8 image from Docker hub
FROM node:10

WORKDIR /server

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy rest of the application csource code
COPY . .
