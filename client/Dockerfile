FROM node:12.9.1-alpine

RUN mkdir -p /src/app/client
WORKDIR /src/app/client

COPY package.json /src/app/client
COPY package-lock.json /src/app/client

RUN npm install

COPY . /src/app/client

CMD ["npm", "start"]