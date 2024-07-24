FROM node:20.15.1-alpine3.20 as node

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]