FROM node:14.15-alpine as frontend-stage

LABEL maintainer="Robioki"

WORKDIR /var/www/html/frontend

COPY . .

EXPOSE 3000

CMD [ "yarn", "dev" ]
