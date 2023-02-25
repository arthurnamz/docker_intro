FROM node:16-alpine
docker run
WORKDIR /frontend

COPY package*.json ./

RUN npm install

COPY . .d

EXPOSE 3000

CMD npm run dev