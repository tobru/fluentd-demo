FROM nginx:latest

RUN rm /var/log/nginx/access.log && touch /var/log/nginx/access.log
COPY nginx.conf /etc/nginx/nginx.conf
