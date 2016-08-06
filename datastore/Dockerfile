FROM busybox:latest

# RUN adduser -D -g '' -u 1000 -h /home/fluent fluent
# RUN chown -R fluent:fluent /home/fluent

# for log storage (maybe shared with host)
# RUN mkdir -p /fluentd/log

VOLUME /usr/share/elasticsearch/data
VOLUME /var/log/nginx
VOLUME /var/log/fluentd

CMD /bin/sh
