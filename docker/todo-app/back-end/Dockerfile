FROM node:14-alpine

WORKDIR /backend

EXPOSE 3031

ADD node_modules.tar.gz .

COPY . .

CMD [ "npm", "start"]