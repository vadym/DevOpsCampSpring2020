FROM alpine:latest
RUN apk update && apk add \
	python \
	py-pip \
	&& rm -rf /var/cache/apk/* \
  && pip install pip --upgrade \
  && pip install awscli
ENTRYPOINT ["aws"]
