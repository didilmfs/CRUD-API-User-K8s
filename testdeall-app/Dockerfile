FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

RUN chmod 777 entrypoint.sh

EXPOSE 2022

ENTRYPOINT ["/bin/bash", "./entrypoint.sh"]

