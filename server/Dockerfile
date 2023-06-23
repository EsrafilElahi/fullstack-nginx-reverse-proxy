FROM node:lts-buster
WORKDIR /server
COPY ./server/package*.json ./
RUN npm install
COPY ./.env ../.env
CMD ["npm", "run", "start"]