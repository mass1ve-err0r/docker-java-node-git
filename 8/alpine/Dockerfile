FROM timbru31/java-node:8-alpine@sha256:9ea4d3002f1877b3120df3e2e6052b721a7210e452d28372a67eae77def082d2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
