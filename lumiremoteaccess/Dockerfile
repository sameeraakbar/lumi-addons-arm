FROM ghcr.io/home-assistant/base:latest

ENV LANG C.UTF-8

RUN apk add --no-cache tzdata jq openssh vim curl autossh

COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
