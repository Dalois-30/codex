FROM node:latest

WORKDIR /app_client

ADD package.json /app_client/package.json
RUN npm config set registry http://registry.npmjs.org
RUN npm install

ADD . /app_client

EXPOSE 5173

CMD npm run start 