FROM mjgargani/puppeteer:trybe1.0

ADD node_modules.tar.gz /todo-app/tests

COPY . /todo-app/tests

ENTRYPOINT [ "npm", "test" ]