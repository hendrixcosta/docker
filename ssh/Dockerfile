FROM ubuntu

RUN ap-get update && apt-get install openssh-server 

RUN service sshd start

RUN mkdir .ssh

WORKDIR .ssh

COPY '~/.ssh/id_rsa.pub:id_rsa.pub'

RUN cat ida_rsa.pub >> authorized_keys
