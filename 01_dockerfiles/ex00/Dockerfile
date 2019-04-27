# docker build -t ex00 .
# docker run -it --rm ex00

FROM alpine

MAINTAINER hnam <hnam@student.42.fr>

RUN apk update && \
	apk upgrade && \
	apk add vim

ENTRYPOINT vim
