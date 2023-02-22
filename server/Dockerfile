FROM node:latest

WORKDIR /app_server

ADD package.json /app_server/package.json
RUN npm config set registry http://registry.npmjs.org
RUN npm install

ADD . /app_server

EXPOSE 5000

CMD npm run server