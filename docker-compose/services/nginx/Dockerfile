FROM nginx

RUN apt update && \
    apt install -y certbot python3-certbot-nginx vim

COPY letsencrypt /etc/letsencrypt
