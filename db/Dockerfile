FROM cockroachdb/cockroach:v19.2.4

COPY init-data.sh /usr/local/bin

ENV WAIT_VERSION 2.7.2

ADD https://github.com/ufoscout/docker-compose-wait/releases/download/$WAIT_VERSION/wait /wait

RUN chmod +x /wait

CMD ["shell", "/usr/local/bin/init-data.sh db:26257"]
