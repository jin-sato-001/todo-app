FROM node:19.5

WORKDIR /app

COPY package.json ./

RUN npm i

# COPY ./backend/package.json ./
COPY . .

# RUN npm i

CMD ["yarn", "start:dev"]
