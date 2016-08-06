FROM nginx:1.10.1-alpine

# RUN \
#   addgroup -S nginx \
#   && adduser -D -S -h /var/cache/nginx -s /sbin/nologin -G nginx nginx \
# RUN mkdir -p /home/nginx
# RUN chown -R nginx:nginx /home/nginx

# USER root

# RUN adduser -D -u 1000 nginx


# USER nginx

# RUN adduser -D -g '' -u 1000 -h /home/fluent fluent
# RUN chown -R fluent:fluent /home/fluent
#
# RUN chown -R fluent:fluent /var/cache/nginx
# RUN mkdir -p /var/log/nginx
# RUN chown -R fluent:fluent /var/log/nginx
# RUN chown -R fluent:fluent /etc/nginx/
#
# USER fluent

COPY nginx.conf /etc/nginx/nginx.conf
