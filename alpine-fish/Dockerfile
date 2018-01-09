# build from ubuntu 16.04
FROM alpine:3.7

LABEL maintainer = "no_wheree@outlook.com"

# install basic apps
RUN apk update \
    && apk add fish

# run fish when container is launched
CMD ["fish"]