FROM ubuntu:14.04
MAINTAINER waitingkuo <waitingkuo0527@gmail.com>

RUN echo "deb http://repos.mesosphere.io/ubuntu/ trusty main" > /etc/apt/sources.list.d/mesosphere.list
RUN apt-key adv --keyserver keyserver.ubuntu.com --recv E56151BF
RUN apt-get -y update
RUN apt-get -y install mesos=0.26.0-0.2.145
