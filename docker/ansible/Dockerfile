FROM ubuntu:latest

ENV ANSIBLE_HOST_KEY_CHECKING False

RUN apt-get update && \
    apt-get install -y software-properties-common && \
    apt-get update && \
    apt-get install -y ansible ansible-lint

#CMD /bin/bash
CMD ["/sbin/init"]

