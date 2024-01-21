FROM node
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
expose 8080
CMD ["node", "server.js"]
