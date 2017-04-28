FROM yejiancong/centos

MAINTAINER JianCong Ye


RUN yum -y install golang git && yum clean all
RUN yum -y update && yum clean all

ENV GOPATH /go
ENV PATH $GOPATH/bin:$PATH