FROM nginx:latest

COPY docker/nginx.conf /etc/nginx/nginx.conf
COPY docker/html /usr/share/nginx/html/

RUN chown -R nginx:nginx /usr/share/nginx/html/