FROM node:20

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm isntall

COPY . .

EXPOSE 3001

CMD ["node", "server.js"]