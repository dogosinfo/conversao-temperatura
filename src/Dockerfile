FROM node:14
WORKDIR /app
EXPOSE 8080
COPY . .
RUN npm ci --silent
ENTRYPOINT node server.js