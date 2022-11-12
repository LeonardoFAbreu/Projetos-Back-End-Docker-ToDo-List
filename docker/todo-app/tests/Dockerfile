FROM node:14-alpine AS todotests

WORKDIR /todo-app/tests

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

CMD [ "npm", "test" ]

