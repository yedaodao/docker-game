FROM node:6.6.0

RUN mkdir -p /var/ui/build
RUN mkdir -p /var/ui/output
WORKDIR /var/ui/build
VOLUME ["/var/ui/output"]
RUN touch test
CMD ["tar", "-zcvf", "/var/ui/output/test.tar.gz", "./test"]
