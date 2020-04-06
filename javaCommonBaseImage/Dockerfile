FROM openjdk:14-alpine

MAINTAINER xiaodong 

RUN  apk update && apk upgrade && apk add netcat-openbsd && apk add curl \
	&& apk add --no-cache bash \
        bash-doc \
        bash-completion \
	&& rm -rf /var/cache/apk/*

CMD ["/bin/sh"]
