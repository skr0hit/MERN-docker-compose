FROM node:24-alpine3.20

WORKDIR /app

RUN npm install -g npm

COPY . .

RUN npm install

EXPOSE 5173

CMD [ "npm","run","dev" ]