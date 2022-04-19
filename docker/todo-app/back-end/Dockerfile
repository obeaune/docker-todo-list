FROM node:14-alpine
WORKDIR /app
ADD node_modules.tar.gz ./
COPY . .

ENTRYPOINT [ "npm", "start" ]
EXPOSE 3001
