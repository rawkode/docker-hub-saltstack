FROM centos:7

RUN curl -L https://bootstrap.saltstack.com | sudo sh -s -- stable -M -X

CMD ["salt-master --log-level=debug"]
