FROM alpine

RUN  apk add --no-cache bash

WORKDIR /app

COPY ./project2/entrypoint.sh .
RUN chmod +x entrypoint.sh

ENTRYPOINT  ["/app/entrypoint.sh"]