FROM node:18.19.0-alpine3.19
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
#USER marlon
#HEALTHCHECK --interval=30s --timeout=30s --start-period=5s --retries=3 CMD [ "executable" ]
EXPOSE 8080
CMD ["node", "server.js"]
