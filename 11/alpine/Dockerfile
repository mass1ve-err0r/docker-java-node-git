FROM timbru31/java-node:11-alpine@sha256:0377099da8924f889bc7074d47175c1ca224c76dbffd716f3b51a09054555288
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
