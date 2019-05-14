FROM node:7
WORKDIR /app
COPY ./nodejs-app/package.json /app
COPY ./nodejs-app/index.js /app
RUN npm install
EXPOSE 8081
CMD node index.js
