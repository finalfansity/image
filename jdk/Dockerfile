FROM centos:7
MAINTAINER test
ADD jdk-8u231-linux-x64.tar.gz /usr/local/
ADD cos_migrate_tool_v5-master.tgz /root/
ENV JAVA_HOME /usr/local/jdk1.8.0_231
ENV CLASSPATH $JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
ENV PATH $PATH:$JAVA_HOME/bin
