FROM mjgargani/puppeteer:trybe1.0
WORKDIR /home/vitorlichoti
COPY . .
ADD node_modules.tar.gz ./docker/todo-app/tests/Dockerfile
CMD ["npm", "test"]
