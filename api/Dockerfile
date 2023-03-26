FROM node:alpine

WORKDIR /beckend

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 5000

CMD [ "npm", "run", "dev"]