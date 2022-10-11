FROM node:14-alpine

EXPOSE 3031

ADD node_modules.tar.gz /todo-app/back-end

COPY . /todo-app/back-end

ENTRYPOINT [ "npm", "start"]