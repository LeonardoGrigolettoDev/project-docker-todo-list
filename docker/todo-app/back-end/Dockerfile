FROM node:14
EXPOSE 3001
WORKDIR /docker/todo-app/back-end
COPY ./node_modules.tar.gz .
COPY ./ .
RUN npm install
CMD ["npm", "start"]