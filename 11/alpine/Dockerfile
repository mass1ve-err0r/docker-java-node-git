FROM timbru31/java-node:11-alpine@sha256:72fe8acdde78db2648c23e46bbafcf27ccd62746ba10e95ca8f3384c1b441199
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
