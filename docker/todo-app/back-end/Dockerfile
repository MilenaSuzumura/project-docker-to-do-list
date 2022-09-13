FROM node:14

WORKDIR /todo-app/back-end

COPY node_modules.tar.gz ./

RUN npm install

COPY . .

EXPOSE 3001

ENTRYPOINT ["npm"]

CMD ["start"]
