FROM timbru31/java-node:11-alpine@sha256:26746d547361d6ad461140df5640e56464dcf2aa680b14a86a0953107229fc2f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
