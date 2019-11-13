FROM alpine:3.7

RUN apk update \
	&& apk upgrade \
	&& apk add bash \
	&& apk add bash-doc \
	&& apk add bash-completion \
	&& apk add haproxy

COPY haproxy.cfg /etc/haproxy

EXPOSE 8080