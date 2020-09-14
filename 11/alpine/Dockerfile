FROM timbru31/java-node:11-alpine@sha256:407474b34f3807d13b21cd9dd79baa938b338721f1593c4aa430cf0b1dee2589
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
