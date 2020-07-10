FROM timbru31/java-node:11-alpine@sha256:5c075b811e64d89b3916cfe254b49adc2c9162465fc9987215eb28b8bdaca835
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
