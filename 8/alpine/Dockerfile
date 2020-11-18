FROM timbru31/java-node:8-alpine@sha256:d744a3037429496a426a2baee3c288178292870a25ced545d02ec2f934a7f7ab
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
