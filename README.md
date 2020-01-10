# docker
docker shell

- openjdk  
增加fontconfig 的解决方案
RUN apk add --update ttf-dejavu && rm -rf /var/cache/apk/*
RUN fc-cache --force