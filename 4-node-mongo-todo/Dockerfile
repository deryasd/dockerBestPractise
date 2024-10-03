FROM node:18.12.0
WORKDIR /opt/node-todo-app
COPY . .
ENV PORT=4000
EXPOSE 4000
RUN npm install
ENTRYPOINT [ "node" ]
# CMD ["node", "app.js"]
CMD ["app.js"]