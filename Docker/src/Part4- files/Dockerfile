FROM nginx

USER root

COPY ./main.c /home/main.c
COPY ./server_run.sh /home/server_run.sh
COPY ./nginx.conf /etc/nginx/nginx.conf

EXPOSE 8080

RUN apt-get update; \
  apt-get install -y gcc spawn-fcgi libfcgi-dev

WORKDIR /home/

ENTRYPOINT ["sh", "./server_run.sh"]
