### Dockerfile
#
#   See https://github.com/ali-shaikh/docker

FROM alpine:latest
LABEL maintainer="Ali Shaikh <ali.az.shaikh@gmail.com>"

RUN apk update && apk upgrade && \
	apk add ca-certificates bash && \
	rm -rf /var/cache/apk/*