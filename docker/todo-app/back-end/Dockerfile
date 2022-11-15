FROM node:14
EXPOSE 3001
WORKDIR /docker/todo-app/back-end/src
ADD ../node_modules.tar.gz .
COPY ../ .
RUN npm install
CMD ["npm", "start"]