FROM centos:centos7.5.1804
COPY readme /tmp
RUN yum install -y httpd systemd; yum clean all
RUN systemctl enable httpd || true
RUN systemctl start httpd || true
#CMD ["/usr/sbin/init"]
CMD ["/bin/bash"]

