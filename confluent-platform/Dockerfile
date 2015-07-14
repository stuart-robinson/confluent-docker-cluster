FROM gliderlabs/alpine

RUN apk update && apk add bash openjdk7-jre-base \
    && apk add wget \
    && wget http://packages.confluent.io/archive/1.0/confluent-1.0-2.10.4.zip \
    && apk add unzip \
    && unzip confluent-1.0-2.10.4.zip \
    && rm confluent-1.0-2.10.4.zip \
    && ln -s /confluent-1.0/bin/[^.]* /usr/bin \
    && ln -s /confluent-1.0/share/java /usr/share/java \

