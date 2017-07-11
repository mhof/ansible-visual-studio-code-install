FROM fedora:25

RUN dnf install -y python2 python2-dnf libselinux-python ansible sudo which tar gzip \
  && useradd ansible-test-user -m -s /bin/bash \
  && echo "ansible-test-user 	ALL=(ALL)	NOPASSWD: ALL" >> /etc/sudoers

USER ansible-test-user
WORKDIR /home/ansible-test-user