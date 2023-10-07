FROM node:19.5

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

CMD ["npm", "run", "dev"]
