FROM node:18.18.2-alpine3.18

WORKDIR /usr/app

COPY ./package.json WORKDIR

RUN yarn

EXPOSE 4000

CMD ["yarn", "dev:api"]