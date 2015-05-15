FROM ubuntu:14.04

ENV           DEBIAN_FRONTEND noninteractive
RUN           apt-get -y update && \
 		apt-get -y install collectd

ADD	      ./collectd/collectd.conf /etc/collectd/

CMD           ["collectd", "-f"]
