FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /user/src/todo-app/tests

ADD node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]
