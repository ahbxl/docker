FROM openjdk:8-jdk-alpine
RUN apk update && apk add tzdata && ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN apk add --update ttf-dejavu && rm -rf /var/cache/apk/*
RUN fc-cache --force