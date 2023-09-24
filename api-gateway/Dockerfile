
FROM node:18-alpine

WORKDIR /app

COPY package*.json ./

# Install app dependencies
RUN npm install

COPY . .

CMD [ "npm", "start" ]
