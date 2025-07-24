FROM ubuntu:22.04

RUN apt-get update && \
    apt-get install -y python3 python3-pip sshpass iputils-ping && \
    pip3 install ansible

CMD ["sleep", "infinity"]