FROM nginx

MAINTAINER sage
RUN rm /etc/nginx/conf.d/default.conf
COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx
