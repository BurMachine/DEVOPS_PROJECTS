FROM nginx

RUN mkdir "server"

COPY main.c /server
COPY server_run.sh /server
COPY nginx.conf etc/nginx/

RUN apt-get update; \
  apt-get install -y gcc spawn-fcgi libfcgi-dev

WORKDIR /server/

CMD ["sh", "./server_run.sh"]
