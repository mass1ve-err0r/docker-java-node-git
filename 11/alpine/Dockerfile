FROM timbru31/java-node:11-alpine@sha256:3458f161ee19feef5b43a662cee3df9e6ba74c21d083e79b4f5044b17ca45216
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
