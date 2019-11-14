FROM alpine:latest


RUN apk update \
	&& apk upgrade \
	&& apk add bash \
	&& apk add bash-doc \
	&& apk add bash-completion \
	&& apk add openrc --no-cache \
	&& apk add haproxy

COPY haproxy.cfg /etc/haproxy
# RUN rc-service haproxy start

EXPOSE 8080