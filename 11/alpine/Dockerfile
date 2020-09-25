FROM timbru31/java-node:11-alpine@sha256:fcb151e27531d84f10712ce04ed2beb27a7e842384982270f46ee7c945ce4b81
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
