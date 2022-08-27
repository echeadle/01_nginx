FROM nginx:1.23.1

RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf

COPY ./demo/.  /sites/demo/

#COPY content /usr/share/nginx/html
COPY config /etc/nginx


VOLUME /usr/share/nginx/html
VOLUME /etc/nginx



