FROM nginx:latest

EXPOSE 80

RUN rm /etc/nginx/conf.d/default.conf
# COPY proxy.conf /etc/nginx/conf.d/
# COPY reverse-proxy.conf /etc/nginx/conf.d/

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf