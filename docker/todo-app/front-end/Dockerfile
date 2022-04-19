FROM node:14-alpine
ADD node_modules.tar.gz ./
WORKDIR /app
COPY package*.json ./
COPY . .
RUN npm install

EXPOSE 3000
