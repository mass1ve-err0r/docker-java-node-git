FROM timbru31/java-node:11-alpine@sha256:0555ba65e850cbf7e99b645061ab65d33fa850895ea55d5b274224addef93d95
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
