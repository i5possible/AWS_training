From node:14-alpine

COPY package.json package-lock.json .
RUN npm install
COPY . ./

EXPOSE 3000

ENTRYPOINT ["node", "app.js"]
