FROM node:lts-alpine
RUN apk update && apk upgrade && npm install http-server -g
ENTRYPOINT ["http-server"]
