FROM ubuntu:20.04

MAINTAINER Sean <circlelang@gmail.com>

RUN apt-get update && \
  apt-get install -y binutils libstdc++-10-dev wget git && \
  wget -P /home https://www.circle-lang.org/debian/build_181.tgz && \
  tar xvf /home/build_181.tgz -C /usr/bin && \
  chmod +x /usr/bin/circle && \
  git clone https://www.github.com/seanbaxter/circle /home/circle_docs
