FROM node:slim

WORKDIR /app

COPY . .

RUN npm install

COPY .env .env

EXPOSE 3000

CMD ["npm","start"]
