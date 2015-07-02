FROM gitinsky/baseimage:0.1.8
MAINTAINER Git In Sky <support@gitinsky.com>

ENV JAVA_HOME=/jdk1.8.0_45
RUN apt-get update && apt-get install wget && wget http://ns2.1888.spb.ru/jdk-8u45-linux-x64.tar.gz && tar xzf /jdk-8u45-linux-x64.tar.gz && rm /jdk-8u45-linux-x64.tar.gz
