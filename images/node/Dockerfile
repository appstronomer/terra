FROM alpine:3.18.2
LABEL project=terra
RUN apk update && apk add sudo 
RUN echo "ALL ALL=(ALL:ALL) ALL" >> /etc/sudoers
RUN apk add npm
ENV npm_config_cache=/volume/cache
ENV npm_config_prefix=/volume/node_modules
