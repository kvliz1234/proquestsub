#dockerfile
FROM node:16-alpine
## create app directory
WORKDIR /my-app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "index.js"]


