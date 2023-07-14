FROM alpine:3.18.2
LABEL project=terra
RUN apk update && apk add sudo 
RUN echo "ALL ALL=(ALL:ALL) ALL" >> /etc/sudoers
RUN apk add python3 py3-pip
ENV PIP_CACHE_DIR=/volume/cache
ENV PIP_TARGET=/project/pip_modules
ENV PYTHONPATH=/project/pip_modules
