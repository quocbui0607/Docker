FROM node:14-alpine

WORKDIR /app

COPY ./package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGO_INITDB_ROOT_USERNAME=
ENV MONGO_INITDB_ROOT_PASSWORD=

CMD ["node", "app.js"]