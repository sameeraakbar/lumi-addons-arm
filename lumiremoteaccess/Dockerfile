ARG BUILD_FROM=ghcr.io/home-assistant/base:3.19
FROM $BUILD_FROM

ENV LANG C.UTF-8

RUN apk add --no-cache tzdata jq openssh vim curl autossh

COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
