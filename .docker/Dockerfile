FROM nginx

RUN apt-get update && apt-get install -y certbot

COPY ./.docker/nginx.conf /etc/nginx/nginx.conf
COPY ./.docker/ssl.conf /etc/nginx/includes/ssl.conf

EXPOSE 80 443
