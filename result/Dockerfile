##
## EPITECH PROJECT, 2023
## DEVOPS
## File description:
## dockerfile
##

FROM node:20-alpine

WORKDIR /app

COPY package.json package-lock.json ./
RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "server.js"]
