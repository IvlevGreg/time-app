FROM node:alpine

WORKDIR ./app

COPY package-lock.json package.json ./

RUN npm i

COPY . .

EXPOSE 5000

CMD ["npm","run", "dev"]
