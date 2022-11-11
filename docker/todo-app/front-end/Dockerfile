FROM node:14-alpine AS todofrontend

EXPOSE 3000

WORKDIR /user/src/todo-app/front-end

ADD node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]
