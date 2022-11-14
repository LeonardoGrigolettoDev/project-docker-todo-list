FROM node:14
EXPOSE 3001
ADD ./node_modules.tar.gz .
COPY ./ .
WORKDIR /docker/todo-app/back-end/src
RUN npm install
RUN npm start