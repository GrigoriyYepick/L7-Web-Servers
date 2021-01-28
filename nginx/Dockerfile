FROM openresty/openresty:alpine

COPY nginx.conf /etc/nginx/
COPY ./images/ /etc/nginx/images
COPY ./lua/ /etc/nginx/lua

RUN apk add curl

EXPOSE 80 81 443
