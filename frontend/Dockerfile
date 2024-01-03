FROM node:alpine

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm i

EXPOSE 3000

COPY . .

CMD ["npm","run", "dev"]

