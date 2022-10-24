ARG NGINX_VERSION=1.19-alpine-perl
FROM nginx:$NGINX_VERSION
RUN rm /etc/nginx/conf.d/default.conf
ADD ./nginx-conf/* /etc/nginx/conf.d/