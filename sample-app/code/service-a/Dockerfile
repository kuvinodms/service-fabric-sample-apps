FROM stefanscherer/node-windows:6.9.4
EXPOSE 80

RUN mkdir C:\\app 
WORKDIR C:\\app
COPY package.json .
RUN npm install
COPY . .

CMD ["node", "server.js"]
