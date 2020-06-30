FROM timbru31/java-node:8-alpine@sha256:b46766b33f8e2509995962b8fcd2aff3092121bc65ab23ae66e0f71d285544a7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
