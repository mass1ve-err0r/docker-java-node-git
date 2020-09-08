FROM timbru31/java-node:11-alpine@sha256:16f86a9aab9bac1062b31f53324fe53704643833120157de0dd2f02f481d884b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
