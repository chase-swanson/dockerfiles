FROM node:16-alpine
RUN apk upgrade
WORKDIR /app

RUN rm -rf /usr/local/lib/node_modules/npm
RUN chown -R node .
USER node