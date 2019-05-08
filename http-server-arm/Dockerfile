FROM balenalib/armv7hf-alpine-node:10
RUN [ "cross-build-start" ]
RUN apk update && apk upgrade && npm install http-server -g
ENTRYPOINT ["http-server"]
RUN [ "cross-build-end" ]

