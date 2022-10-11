FROM node:14
WORKDIR /home/vitorlichoti
COPY . .
ADD node_modules.tar.gz ./docker/todo-app/back-end/Dockerfile
EXPOSE 3001
CMD ["npm", "start"]