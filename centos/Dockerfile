FROM centos:7

RUN curl -L https://bootstrap.saltstack.com | sh -s -- -M -X stable

CMD ["salt-master --log-level=debug"]
