FROM node:18-slim

WORKDIR /usr/src/

COPY package.json package-lock.json ./

RUN npm install

WORKDIR /usr/src/app

COPY . .

EXPOSE 3000

CMD ["npm", "run", "dev"]