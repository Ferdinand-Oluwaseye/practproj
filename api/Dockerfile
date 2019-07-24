FROM node:10-alpine
ENV MONGO_HOST = mongo
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT ["/usr/local/bin/node", "index.js"]
