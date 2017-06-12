#
# This image is modified version of lewuathe/hadoop-slave
# Author: Karol Majek
# Date:   2017 Jun,11

FROM lewuathe/hadoop-base:latest
MAINTAINER lewuathe

ADD bootstrap.sh /etc/bootstrap.sh
RUN chown root:root /etc/bootstrap.sh
RUN chmod 700 /etc/bootstrap.sh

ENV BOOTSTRAP /etc/bootstrap.sh

CMD ["/etc/bootstrap.sh", "-bash"]
