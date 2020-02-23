FROM node:lts-alpine3.9
RUN npm install socket.io
RUN npm install express
COPY ./run-signaling-server.sh /run-signaling-server.sh
COPY ./signaling-server.js /signaling-server.js
