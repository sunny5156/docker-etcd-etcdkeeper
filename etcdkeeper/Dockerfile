FROM alpine

ADD ./ /etcdkeeper/


RUN chmod +x /etcdkeeper/etcdkeeper

WORKDIR /etcdkeeper

ENTRYPOINT [ "./etcdkeeper" ]