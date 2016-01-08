# vim: set ft=Dockerfile et sw=2 ts=2 sts=2 tw=0:
FROM jrdasm/salix-base:14.1
MAINTAINER JRD <jrd@salixos.org>
RUN slapt-get --add-keys && \
    slapt-get --update
WORKDIR /root
ENV TERM xterm-color
CMD ["bash"]
