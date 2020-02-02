FROM timbru31/java-node:8-alpine@sha256:00806bace28b5f4e325cba7fdb295811f59dfc0dd79260cbb5c94b2665a78123
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
