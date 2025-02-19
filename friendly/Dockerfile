FROM amazon/amazon-ecs-network-sidecar:latest

MAINTAINER Ihor Kohut

RUN yum install -y iputils.x86_64 tcping.x86_64 smtpping.x86_64 mtr.x86_64 ioping.x86_64 GeoIP.x86_64 IP2Location.x86_64 prettyping.noarch httping.x86_64

RUN mkdir -p /home/work

ENV IHOR=Ihor

WORKDIR /home/work

CMD ["/bin/bash"]
