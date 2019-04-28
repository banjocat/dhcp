FROM ubuntu:xenial

RUN apt-get update && apt-get install -y \
    dnsutils \
    nagios-plugins

RUN ln -s /usr/lib/nagios/plugins/check_dhcp /bin/check_dhcp
