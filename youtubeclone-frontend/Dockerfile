FROM node:slim

WORKDIR /app

COPY youtubeclone-frontend .

RUN npm install

COPY youtubeclone-frontend/.env .env

EXPOSE 3000

CMD ["npm","start"]
