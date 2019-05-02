FROM centos:centos7.5.1804
COPY readme /tmp
RUN systemctl enable httpd && systemctl start httpd
CMD ["/usr/sbin/init"]

