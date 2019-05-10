FROM node

RUN mkdir -p /var/node
ADD ../00-apps/weather-app /var/node/
WORKDIR /var/node
RUN npm install
EXPOSE 3000
CMD ./bin/www
