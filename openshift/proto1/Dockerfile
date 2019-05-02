FROM centos:centos7.5.1804
COPY readme /tmp
RUN yum install -y httpd
RUN systemctl enable httpd && systemctl start httpd
CMD ["/usr/sbin/init"]

