FROM jenkins
MAINTAINER Tomas Markauskas <tomas@markauskas.lt>

ADD plugins.txt /usr/share/jenkins/plugins.txt
RUN /usr/local/bin/plugins.sh /usr/share/jenkins/plugins.txt
