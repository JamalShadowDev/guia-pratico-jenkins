FROM node:21.6.0-alpine3.18
WORKDIR /app
COPY src/package*.json ./
RUN npm install
COPY src/ . 
EXPOSE 8088
CMD ["node", "server.js"]