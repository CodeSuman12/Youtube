FROM node:slim

WORKDIR /app

COPY yotubeclone-frontend .

RUN npm install

COPY yotubeclone-frontend/.env .env

EXPOSE 3000

CMD ["npm","start"]
