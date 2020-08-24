FROM timbru31/java-node:11-alpine@sha256:89cad4868db62929be3cdd14eb21b6deed53c3901fbd36bb8835533e318f4f59
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
