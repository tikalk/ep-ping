FROM alpine:3.15.4

RUN apk add --no-cache curl

RUN mkdir -p /opt/tikal/

WORKDIR /opt/tikal/

COPY poller.sh /opt/tikal/poller.sh

CMD [ "/opt/tikal/poller.sh" ]
