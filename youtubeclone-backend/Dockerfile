FROM node:slim

WORKDIR /app

COPY youtubeclone-backend .

RUN npm install

COPY youtubeclone-backend/.env .env

EXPOSE 5000 

CMD ["npm","start"]
