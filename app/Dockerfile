FROM node:15

WORKDIR /app

COPY package*.json ./

RUN npm install
RUN npm install express
RUN npm install mongoose

COPY . .

EXPOSE 8080

CMD ["node", "app.js"]

