FROM timbru31/java-node:8-alpine@sha256:262c7650e4fd0735c33e2089ca1888d5796566010eaf8ca347c1cba5b8c4538b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
