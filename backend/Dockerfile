FROM node_20-alpine

WORKdIR /app

COPY package*.json ./
RUN npm install --production

COPY..

EXPOSE 5000

CMD ["node" "server.js"]