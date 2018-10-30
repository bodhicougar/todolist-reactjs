FROM node:8.12.0
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN node -v
RUN npm -v
RUN npm install -g nodemon

EXPOSE 3000
CMD [ "npm", "start" ]