FROM openjdk:16-alpine
RUN apk upgrade
RUN addgroup -g 1000 javauser &&\
  adduser -u 1000 -G javauser -s /bin/sh -D javauser
USER javauser