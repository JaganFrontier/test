FROM node:18-alpine3.14
RUN npm i -g typescript ts-node
WORKDIR /
COPY . .
RUN npm install
EXPOSE 3000
CMD ["node", "app.js"]