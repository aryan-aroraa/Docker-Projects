# stage 1
FROM node:26 AS builder

WORKDIR /app

COPY package.json .

RUN npm install

#stage 2
FROM node:26-slim

WORKDIR /app

COPY --from=builder /app/node_modules ./node_modules

COPY . .

CMD ["node", "index.js"]


