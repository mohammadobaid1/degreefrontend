FROM node:8.9

WORKDIR /nodeapp

COPY package*.json ./

RUN npm install

COPY . .




CMD [ "npm", "start" ]

