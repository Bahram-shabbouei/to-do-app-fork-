FROM node:22.14-alpin

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY . .

EXPOSE 3050

CMD ["node", "server.js"]d