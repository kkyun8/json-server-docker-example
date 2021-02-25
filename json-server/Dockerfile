FROM node:10.15.0

RUN npm install -g json-server

WORKDIR /data

CMD json-server --watch db.json --routes route.json --host 0.0.0.0 -p 5000