FROM ubuntu

MAINTAINER Takuya UESHIN ueshin@happy-camper.st
 
RUN apt-get update
RUN apt-get install -y software-properties-common

RUN add-apt-repository -y ppa:webupd8team/java 
RUN apt-get update
RUN echo oracle-jdk7-installer shared/accepted-oracle-license-v1-1 select true | sudo /usr/bin/debconf-set-selections
RUN apt-get install -y oracle-jdk7-installer
