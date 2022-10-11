FROM node:14
WORKDIR /home/vitorlichoti
COPY . .
ADD node_modules.tar.gz ./docker/todo-app/front-end/Dockerfile
EXPOSE 3000
CMD ["npm", "start"]
