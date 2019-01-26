FROM node:8.15.0-alpine

RUN mkdir /app

WORKDIR /app

COPY . .

RUN rm -Rf node_modules

RUN npm i

RUN npm i -g @angular/cli

CMD ["ng","serve","--host=0.0.0.0"]

