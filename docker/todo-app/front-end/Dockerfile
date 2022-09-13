FROM node:14

WORKDIR /todo-app/front-end

COPY node_modules.tar.gz ./

RUN npm install

COPY . .

EXPOSE 3001

ENTRYPOINT ["npm"]

CMD ["start"]