FROM node:14-alpine

COPY package.json package.json .
RUN npm install
COPY . ./

EXPOSE 3001

ENTRYPOINT npm run start
