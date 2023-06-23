FROM node:lts-buster
WORKDIR /client
COPY ./client/package*.json ./
RUN npm install
CMD ["npm", "run", "start"]