#ARG FROM_BASE=jwilder
#ARG NGINX_PROXY_TAG=alpine
ARG FROM_BASE=nginxproxy
ARG NGINX_PROXY_TAG=1586

FROM ${FROM_BASE}/nginx-proxy:${NGINX_PROXY_TAG}
#FROM jwilder/nginx-proxy:alpine

COPY uploadsize.conf /etc/nginx/conf.d/uploadsize.conf
