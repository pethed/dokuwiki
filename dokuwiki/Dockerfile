FROM debian

MAINTAINER Peter

RUN apt-get update && apt-get -y install wget

RUN wget http://download.dokuwiki.org/src/dokuwiki/dokuwiki-stable.tgz
RUN tar -xzvf dokuwiki*.tgz --strip-components=1
